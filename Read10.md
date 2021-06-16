# In memory storage
## Understanding the JavaScript Call Stack
1.What is a ‘call’? Its function invocation.

2.How many ‘calls’ can happen at once?

3.What does LIFO mean? Last in, first out

4.Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

5.What causes a Stack Overflow?

When a recursive function (which calls itself function) without an exit point exists, a stack overflow occurs.

## JavaScript error messages
1.What is a ‘refrence error? You get this type of os error when you try to use a variable not yet declared.

2.What is a ‘syntax error’? This happens when something cannot be parsed in syntax terms.

3.What is a ‘range error’? If you are trying to handle an object with a certain length and give it an invalid length.

4.What is a ‘tyep error’?

Such types of errors appear when you have incompatible types number, string, and so on such as accessing a property in an undefined variable.

5.What is a breakpoint? Its a point in the code, which will make your program stop at that point and help you debugg your code at that point.

6.What does the word ‘debugger’ do in your code? It adds a breakpoint to that, and from that point you can step-by-step through your code.

## Stack Call
The call stack is used primarily to call functions (call). Because of the call stack, function(s) are executed from top to bottom, one by one. It means a synchronous call stack. A call stack is a data framework used to store and manage function invocations temporarily with the Last In, First Out (LIFO) principle