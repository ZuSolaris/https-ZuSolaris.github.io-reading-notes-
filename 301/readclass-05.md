# Reading Assignment 5

## React Docs - Thinking in React

https://reactjs.org/docs/thinking-in-react.html

**What is the single responsibility principle and how does it apply to components?**

It means that the component should only serve one purpose. If the component starts to have additional capabilities it should be broken down into smaller components.

**What does it mean to build a ‘static’ version of your application?**
When you are making a static version of an app it refers to using other components. Passing data using props. It doesn't have interactivity however due to the lack of having a state. 

**Once you have a static application, what do you need to add?**
Once the static application is operable, you should proceed by making state function and wire it up.


**What are the three questions you can ask to determine if something is state?**

According to React documentation the its as follows: 

Is it passed in from a parent via props? If so, it probably isn’t state.

Does it remain unchanged over time? If so, it probably isn’t state.

Can you compute it based on any other state or props in your component? If so, it isn’t state.

**How can you identify where state needs to live?**
You can identify what lives in state by identifying which component mutates or own the state.


## Higher-Order Functions

https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK

**What is a “higher-order function”?**

Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.

**Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?**

Line 2 of this function is basically a super condensed version of a true or false. Its saying if m is greater than n return true and if it's not return false.


**Explain how either map or reduce operates, with regards to higher-order functions.**
Map

The map function transforms an array by applying functions to all of its elements and buidling a new array with returned values. Reduces having to state arrays and functions, when you can just refer to them.

Reduce

If you use reduce on an array with at minimum an array in it. But it takes the first value as it's start value and assigns it and reduces at the second value. 






[Back to Home](https://zusolaris.github.io/reading-notes/)

