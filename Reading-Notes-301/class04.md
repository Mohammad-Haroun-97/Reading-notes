 React and Forms :

## What is a â€˜Controlled Componentâ€™?

- it is one that takes its current value through props and notifies changes through callbacks like onChange.

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

- we should do update the state as soon as the user enter the data or change it becaues the setState function is async function.

## How do we target what the user is entering if we have an event handler on an input field?

- handleChange(event) { this.setState({value: event.target.value}); }
## Controlled Components



In HTML, form elements such as <input>, <textarea>, and <select> typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().
We can combine the two by making the React state be the â€œsingle source of truthâ€. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a â€œcontrolled componentâ€.

----



  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }










condition ? exprIfTrue : exprIfFalse


==============



**x===y?   true: false**
