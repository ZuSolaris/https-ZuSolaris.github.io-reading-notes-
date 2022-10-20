# Reading Assignment 4

React Docs - Forms

## Controlled Components
https://reactjs.org/docs/forms.html

 Controlled components are those where a form's data is handled by the component's state.

**Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

We should update the state as soon as they enter them, so their changes can appear dynamically across all parts of the code. Without the need to reiterate it. 

**How do we target what the user is entering if we have an event handler on an input field?**

When you are dealing with multiple inputs, adding a name attribute to each element to allow the handler function to choose based on event.target.name.


## Ternary Operators

https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff

**Why would we use a ternary operator?**
The ternary operator allows us to take conditionals and compact them into a line of code.

**Rewrite the following statement using a ternary statement:**

if(x===y){
  console.log(true);
} else {
  console.log(false);
}


**Ternary Version**

if(x===y) console.log(true) : console.log(false);

[Back to Home](https://zusolaris.github.io/reading-notes/)