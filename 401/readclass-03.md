# Readings

## Review: ES6 Classes

### Classes are a template for creating ____.

Classes are essentially a template for creating 'special functions'

### Can a class declaration be hoisted?

A class will ultimately reject being hoisted because they have to be defined before they are constructed.

### How would you describe a constructor and contextual “this” to a non-technical friend?

You have have a cookie cutter and the cookie cutter has its features that will be applied to the cookie everytime it is applied. The contextual this refers to the cookies that result from the cookie cutter.



## Using Express Routing


### Within Express, what does routing refer to?

Routing referes to how an application's endpoints respond to client requests. 

### What is the difference between a route path and a route method?

A route method is derived from a HTTP method and attached to an instance of an express class, where as a route path can be used in conjunction with a method to create an end point.

### When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

If a callback function aka handler has more than one arguement is than require to provide next to the callback function and call next() to provide control to the next call back.


## Express Routing

### What is an Express Router?

An express router is an mini instance of the express application, it only contains the routing functionality.


### By what mean do we initialize express.Router() in an express server?

When you intialize the express you are essentially creating a new router for usage.

### What do we use route middleware for?

Route middleware in Express is a way to do something before a request is processed. like checking log, authentication before actually reaching out to the user.


## Reflection

### What are your learning goals after reading and reviewing the class README?

My goal for sure is to be able to make proper and well developed authentcation processes, I'd also definitely like to be able to handle all of the CRUD operations without putting much thought into it. I'd also like to look into what Sequelize means and does.

[Back to Home](https://zusolaris.github.io/reading-notes/)
