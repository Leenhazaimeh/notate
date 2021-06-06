
# React: Component Lifecycle Events
Based off the diagram mounting happens first then  render happens , then the componentDidMount.
constructor, 
React Updates ,
 render,  
componentDidMount,
 componentWillUnmount,



![](https://miro.medium.com/max/2800/0*0saPKFiTUk6W3FYp)

Mounting, Updating, and Unmounting are the three phases of the component lifecycle.


`"componentDidMount is executed after the first render only on the client side. This is where AJAX requests and DOM or state updates should occur."` 

## What is the big difference between props and state?
Props pass into a component.
 Props is handled outside of that component.
 Props is update it outside the component.
 State is handled inside of that component.
 State is update it inside the component.
 Also ,the difference is that state is something like attributes in OOP : it's something local to a class (component), used to better describe it. Props are like parameters - they are passed to a component from the caller of a component (the parent) : as if you called a function with certain parameters.



The values can be any data type, from strings to functions, objects,when we change the state inside our application

 ## things that we could store in state 
Based on user input :
Input Elements.
Check Box.
Select Box.
