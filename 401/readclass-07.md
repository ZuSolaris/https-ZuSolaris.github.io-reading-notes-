# Reading Assignment 7: Bearer Authorization


## Intro to JWT

### What is a JSON Web Token (JWT)?

A JSON web token is an open standard that defines a compact and self contained way to transfer information between parties in as an object.

### When should we use JSON Web Tokens?

After a log in and a subsequent exchange of information which then allows the user to access the given routes or other services.
### Claims are expected in which structural component of a JWT?

Claims are expected in the payload portion. 



## Are JWTs Secure?

### If I get a JWT and I can decode the payload, how can we call that secure?

There is a shared secret that is transferred between communication, and when the token is signed all can read it but the one who has access to the secret is the only one who modify it, that is why we can call it secret.


### If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature. 

When sending, the sender and receiver both must know the SECRET <---THIS


### Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
Imagine I know a secret language and I want to send it to my friend but unfortunately he doesn't know it. It will look like a garbled mess. This is how concatenated content works with a secret. If both parties know the language then the information can be authenticated.


## Videos

## JWTs Explained
It is open standard, securely transfer ifo between two bodies, and it is digitally signed and trusted. They are very compact and able to travel via get requests in a speedy manner

## Why use JWT?
It is great for authentication in aforementioned details above, and convienent for information exchange.


### JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
This is fantastic for switching from page to page, it is fast and can be transmitted through URL.

### What are the three components (the structure) of a JWT signature?
You have a header, a payload, and a signature. 

Reflection
What are your learning goals after reading and reviewing the class README?

My learning goal is to make a JWT authenication side project.

[Back to Home](https://zusolaris.github.io/reading-notes/)