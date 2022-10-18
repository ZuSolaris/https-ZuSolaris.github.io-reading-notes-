# Reading Assignment 2

##  **React Lifecycle**

https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093

<img src="https://miro.medium.com/max/1400/0*0saPKFiTUk6W3FYp" alt="Life Cycle" width="400"/>

**Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**

According to diagram, it appears the the component renders before the componentDidMount runs!.

**What is the very first thing to happen in the lifecycle of React?**

The very first thing that happens in React is the mounting phase. Which consists of Constructor, staticgetDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.

**Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates**

1.Constructor

2.Render

3.React Updates

4.ComponentDidMount

5.ComponentWillUnmount


**What does componentDidMount do?**
This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. 

Videos

## **React State Vs Props**

Responses are in response to information discussed in the following video!
https://www.youtube.com/watch?v=IYvD9oBCuJI
Your browser does not support the video tag.
</video>


What types of things can you pass in the props?
Titles, Subtitles. 

**What is the big difference between props and state?**

Props are passed into a component and must be updated outside of a component. States are handled within a component and can be updated within.

**When do we re-render our application?**

When ever something is changed in code. You would re render your application. When ever there is a change in state or props.

**What are some examples of things that we could store in state?**

We may store data which may be a string , number, or any complex object!

[Back to Home](https://zusolaris.github.io/reading-notes/)