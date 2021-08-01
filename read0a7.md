# Game of Greed 2


Python Scope & the LEGB Rule
Modifying the Behavior of a Python Scope
global names can be accessed or refrenced globally; from any position in the code. However, they can be updated, edited or modified from within the global scope.

## local names

you can access local names only from inside the local Python scope they were created in or from inside a nested function, but you can’t access them from the global Python scope or from other local scopes.

## nonlocal names

can be accessed from inside nested functions, but they can’t be modified or updated from there.

Python provides the keywords (global and nonlocal) as to change the content of global and nonlocal names, however it is a bad practice.
The global Statement
The statement consists of the global keyword followed by one or more names separated by commas. You can also use multiple global statements with a name (or a list of names). All the names that you list in a global statement will be mapped to the global or module scope in which you define them.

Example:

… counter = 0 # A global name … def update_counter(): … global counter # Declare counter as global … counter = counter + 1 # Successfully update the counter

… global_counter = 0 # A global name … def update_counter(counter): … return counter + 1 # Rely on a local name

UnboundLocalError an error that is shown when trying to access a variable that is not defined in a certain scope.
The nonlocal Statement
The nonlocal statement consists of the nonlocal keyword followed by one or more names separated by commas. These names will refer to the same names in the enclosing Python scope.

it is used in nested functions, it cannot be used in a global or local scope.

Example:

… def func(): … var = 100 # A nonlocal variable … def nested(): … nonlocal var # Declare var as nonlocal … var += 100

A SyntaxError arises when trying to define a nonlocal name using the nonlocal statement and it doesn’t exist in the enclosing scope of the function.