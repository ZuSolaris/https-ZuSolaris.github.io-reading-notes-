# Reading Class #12

## Status Codes Based On REST Methods

### **What each group status means.**

**100’s =** Informational status codes. They tell the client that the header part of the request has been recieved. If it fails it will utilize a different status code.

**200’s =** These are success codes. They tell the client if their request has been accepted.

**300’s =** These are redirection codes. They tell the client that its request was accepted.

**400’s =** These are redirection codes. They tell the client that the resource that they're requesting isn't at the expected location.

**500’s = These are client error codes. They handle invalid server requests.**

**What is a status code 202?**

A status code 202 means that the request is valid. But it's processing will occur in the future.

**What is a status code 308?**

A status code 308 is a permanent redirect.

This means that the clients requested content is being hosted in a new location!

**What code would you use if an update didn’t return data to a client?**

You would use 204 No content.

**What code would you use if a resource used to exist but no longer does?**

404 NOT FOUND! :D

**What is the ‘Forbidden’ status code?**

Status code 403 Not Found.

**Why do we need to pull our MongoDB database string out of our server and put it into our .env?**
This is what allows your server to see and interact with your database. Without it the result is empty objects or arrays.

**What is middleware?**

Middleware is software that provides common services and capabilities to applications outside of what's offered by the operating system.

**What does app.use(express.json()) do?**
Its a built in function for middleware that only parses JSON and only looks at the requests where the content-type header matches the type option.

**What does the /:id mean in a route?**
Its a dynamic variable that changes to whatever the id is put in after the first slash.

**What is the difference between PUT and PATCH?**
PUT is an update to an entire resource where as Patch is an update to partial of the resource.

**How do you make a default value in a schema?**
By inputting empty string markers!

**What does a 500 error status code mean?**
It means that the server encountered an unexpected condition that prevented it from fulfilling the request.

**What is the difference between a status 200 and a status 201?**
200 OK means everything that went through is good and accepted where as. 202 Accepted means that the requested was accepted but still processing.

[Back to Home](https://zusolaris.github.io/reading-notes/)
