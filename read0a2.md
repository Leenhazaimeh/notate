# Testing and Modules
Testing
In Tests We Trust

Unit tests are lines of code that test the input, output along with the code behaviour.

TDD stands for Test-Driven Development.

TDD is > a strategy to think (and write!) tests first.

TDD is basically creating the smallest tests possible, and applying them to the smallest code unit.

the test validates/compares the output of a code according to a preset requirement(expected output)

Unit Test Structure(a convention)
AAA: Arrange, Act and Assert.

Arrange: you need to organize the data needed to execute that piece of code (input); Act: here you will execute the code being tested (exercise the behaviour); Assert: after executing the code, you will check if the result (output) is the same as you were expecting.

The Cycle of Writing a Unit Test
Write a unit test and make it fail ( the feature isn’t there)

Write the feature and make the test pass!

Refactor the code

Final thoughts on TDD
TDD is a smart and effective way to code.
TDD will save you time and effort(though it is hard at the beginning) and will enable better maintanence and development of software.
Recursion
The process in which a function calls itself directly or indirectly

enables solving certain problems easily

In recursive functions it is important to use base condition.

the solution to the base case is provided and the solution of the bigger problem is expressed in terms of smaller problems.
Example

int fact(int n) { if (n < = 1) // base case return 1; else return n*fact(n-1) }}

If the base case is not reached or not defined, then the stack overflow problem may arise.

There are two types of recursion (direct & indirect)

Recursion provides a clean and simple way to write code.

Memory Allocation In Recursion
When any function is called from main(), the memory is allocated to it on the stack. A recursive function calls itself, the memory for a called function is allocated on top of memory allocated to calling function and different copy of local variables is created for each function call. When the base case is reached, the function returns its value to the function by whom it is called and memory is de-allocated and the process continues.

