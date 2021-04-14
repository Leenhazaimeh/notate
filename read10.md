# Ch. 10, “Error Handling & Debugging”
Every statement in a script lives in one of three 
execution contexts: 
1. GLOBAL CONTEXT
2. EVAL CONTEXT (NOT SHOWN)
3. GLOBAL SCOPE


  there are two phases 
of activity:(1: Prepare , 2: Execute )



Error :       Generic error - the other errors 
              are all based upon this error 


Syntax Error:  Syntax has not been followed

 

Ref erenceError: Tried to reference variable  that is not declared/within scope 



TypeError :An unexpected data ype that 
cannot be coerced



Range Error : Numbers not in acceptable range


URI Error :encodeURI ().decodeURI(),and 
similar methods used incorrectly


Eval Error :eva l () function used incorrectly


**NaN 
NOT AN ERROR 
Note: If you perform a mathematical operation using 
a value that is not a number, you end up with the 
value of NaN, not a type error.**


## there are two things you can do with the errors: 
1. : Debug the script to fix errors( is about deduction)
2.  Handle errors gracefully( using try, catch, 
throw, and finally statements. )

