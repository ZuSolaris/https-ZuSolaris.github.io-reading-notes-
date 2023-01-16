## Reading 27 useState()

## Introducing Hooks

**What was the motivation for introducing Hooks?**
It is difficult reuse stateful logic between components. Complex components are too complex. Class components are confusing in general.

**What changes are important regarding implementing Hooks versus Component Classes?**
You dont have to refactor the entire code base. You can reuse state between all of the hierarchy. 

**Hooks allow you to reuse stateful logic without changing ___ _______.**
Your component Hierarchy.

## hooks api

**Name two rules imposed by React Hook usage.**
You can split a component into smaller functions, and you can actually use functional hooks and components together. 

**How would you identify a custom Hook and why might you create one?**
You  can identify a custom Hook by seeing if all state and effects are fully isolated. It will always have a use at the beginning of the naming convention as well. 


## the state hook

**What is a Hook?**
React Hooks are simple JavaScript functions that we can use to isolate the reusable part from a functional component.

**When would I use the useState Hook?**
 To keep track of strings, numbers, booleans, arrays, objects

**If you were to add React state to a function component by declaring a state variable:**
Declare a state a variable called count, and set it to 0.

**What does calling useState do?**
It declares a state variable.

**What do we pass to useState as an argument?**
We pass initial state through the useHook.


**What does useState return?**
Use state consist of an array with two values which is the inital or starting value of the state value.
