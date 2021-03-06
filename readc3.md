# Passing Functions as Props

## What does .map() return?



map() function returns a map object(which is an iterator) of the results after applying the given function to each item of a given iterable (list, tuple etc.) Parameters : fun : It is a function to which map passes each element of given iterable.


## If I want to loop through an array and display each value in JSX, how do I do that in React?

return tbody(
    for (var i = 0; i < numrows; i++) {
        ObjectRow()
    } 
)



**Each list item needs a unique ____.**("key" prop.)

## What is the purpose of a key?
A “key” is a special string attribute you need to include when creating lists

## The Spread Operator

Spread operator allows an iterable to expand in places where 0+ arguments are expected. It is mostly used in the variable array where there is more than 1 values are expected. It allows us the privilege to obtain a list of parameters from an array.
### example of using the spread operator to combine two arrays.




// normal array concat() method





let arr = [1,2,3];




let arr2 = [4,5];
  
arr = arr.concat(arr2);
  
console.log(arr); // [ 1, 2, 3, 4, 5 ]//


## How to Pass Functions Between Components



Pass event handlers and other functions as props to child components:

`<button onClick={this.handleClick}>`

![](data:image/png;base64,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)

