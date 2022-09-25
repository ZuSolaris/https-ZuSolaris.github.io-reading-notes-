
# Reading Assignment 9


## HTML Forms

https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form

**Why are forms so important in web development?**

Forms are extremely important due to the fact that it helps push data to search engines. It also allows the internet to access data from from and make the sites visible. The main point being that web forms are one of the main points of interaction between a user and a web site or application. 

**When designing a form, what are some key things to keep in mind when it comes to user experience?**

When designing a form you want to ensure that plannning ahead will keep your goals in check. It is possible to make a form a much too complex. Meaning, that you might be asking for too many inputs from the form resulting in a loss of users. Key data points should be a focus in the design process.


**List 5 form elements and explain their importance.**

**form**: This is the form element is a container element. But used for storage of forms.

**Input**: The label element is a single line text field. 

**textarea**: This is an element that creates a multiline text field.

**label**:This element takes a input element and assigns a programmatical and visual id.

**button**: This element allows the user to submit a data type or input. 

## JS Events

https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events

**How would you describe events to a non-technical friend?**

So imagine you have your boss they are the event or button. Then you also have the event listener which is the employee. They do things when the boss says to do so. 


**When using the addEventListener() method, what 2 arguments will you need to provide?**

When you using an event listener you need provide a method of invocation and a script to play.

**Describe the event object. Why is the target within the event object useful?**
An event object is used to provide extra features to event handlers. Then you can use the target attribute to actually specify data that needs to be adjusted.


**What is the difference between event bubbling and event capturing?**

https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events

**Capturing**

The browser checks to see if the element's outer-most ancestor (<html>) has a click event handler registered on it for the capturing phase, and runs it if so.
Then it moves on to the next element inside <html> and does the same thing, then the next one, and so on until it reaches the direct parent of the element that was actually clicked.

**Bubbling**

The browser checks to see if the direct parent of the clicked element has a click event handler registered on it for the bubbling phase, and runs it if so.
Then it moves on to the next immediate ancestor element and does the same thing, then the next one, and so on until it reaches the <html> element.



[Back to Home](https://zusolaris.github.io/reading-notes/)