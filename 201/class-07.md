# Reading Assignment 7

## Domain Modeling
Source:https://github.com/codefellows/domain_modeling#domain-modeling
**Explain why we need domain modeling?**

Domain Modeling is a conceptual model of code. It is used to describe many various entities with different behaviors. It stores all of this data and methods within a practice called the object oriented model.

## HTML Basics

Source:https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics


**Why should tables not be used for page layouts?**
Tables make screen accessibility impossible for the visually impaired to access pages, it makes the screen reader sound confusing and much to complex for accessiblity.

It is also bad practice because tables run a risk of making tags messy, they also produce code that is hard to follow and also complex.

Tables will run into compatibility issues across different screen resolutions, browser, and devices due to their nature of interacting of content within.

**List and describe 3 different semantic HTML elements used in an HTML table**

**td**: table data is an element that contains data and participates in the table model.

**th**: table headers or the **th** element adds a special cell that define the type of data that labels columns or headers.

**tr**: tr is an HTML element that defines a row of cells in a table. The row then takes in data from both the **th** and **td** elements.



## Introducing Constructors
sources:https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors

**What is a constructor and what are some advantages to using it?**
Objects literals are nice when you want to create only one object. But expanding upon that while having the same values can seriously become redundant. Constructors can seriously compact and reduce the size of code by just defining functions before hand and then naming the object over those functions, WHILE keeping all the definitions the same.

**How does the term this differ when used in an object literal versus when used in a constructor**

The term this differs completely in fact the method is completely different yet similar and suits the same purpose! Anyways we achieve this by actually referring to the name of the constructor and then access the predefined function that we wish to use.


## Object Prototypes Using A Constructor
Source1: https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object_prototypes
Source2:https://ui.dev/beginners-guide-to-javascript-prototype

**Explain prototypes and inheritance via an analogy from your previous work experience.**

Prototypes are like a redefinable object, they can be created and reused from a template to create various rendtions. They have a feature called inheritence which can then be used to create 'special versions' from those. 

I was an IT in my past life so I guess I can explain in analogy by saying you have many users they all share the same format and style, But then you had the Sys Admins like me, we used the same network like any other users. BUT I had the ability to modify other aspects of the networks. Thats where the inheritance and additional functions would come in. 

[Back to Home](https://zusolaris.github.io/reading-notes/)

