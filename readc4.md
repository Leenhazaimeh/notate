# React and Forms
 

 ### React Docs - Forms


 In React, when handling a form, you’d want a JavaScript function that handles the submission of the form. The function will have access to the form data entered by the user. This technique is called “controlled components”.

 ` the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”. `


A Controlled Component is nothing but a technique of controlling the value of form input elements by Recat.
 The handleChange will keep the React state updated. You can actually type something and see the console logging the most recent value every single time.

Controlled Components In HTML, form elements such as input, textarea, and select typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.

Handling Multiple Inputs When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

 ### The Conditional (Ternary) Operator Explained

  the ternary operator Used to simplify  if-else statements that are used to assign values to variables. The ternary operator is commonly used when assigning post data or validating forms.

Rewrite the following statement using a ternary statement:

  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

-------------
 (x===y)? console.log('true') : console.log('false');




