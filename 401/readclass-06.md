# Readings: Authentication


## Readings

## Securing Passwords

Source: https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html

### Explain to a non-technical friend how you would safely hash and store a password.

Think of storing a password like change, we know the value of it and if organized we can understand it. But throw it in a jar and it will take a while to decipher to organize and find out its value. But if you use an algorithim is like using a change counter that you can just throw a bunch in and it will give you value.

### What is Bcrypt?

Bcrypt is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be.

### Why might you use something like Bcrypt?

Bcrypt minimalizes the possibility of a brute force attack by adding an additional layer of security and changes over a certain timespan making it resitant to brute force attacks.

## Basic Auth

### What is Basic Authentication?
Basic Auth is a simple technique used for enforcing, access contorls to web resources, doesn't require addotional
### What properties are necessary in the header of a Basic Auth request?

Authorization: Credentials which consist of the unique ID and password.

### How are username:password in Basic Auth encoded?

It is endocded using a BASE64 combination of an ID and password.


## OWASP auth cheatsheet

### Define the authentication process to a non-technical recruiter.

The authencation starts when someone requests access to a specific instance of an account. It is authenticated when the servers pass back and forth information to verify if it a user. It's as if you were checking someones ID, and asking the person simulateonously information about where they live and and other identifiers.

### How should your error messaging respond (both HTTP and HTML)? Why?

These are common errors to ensure user maximum security even with the least savy users.

-The user ID or password was incorrect.

-The account does not exist.

-The account is locked or disabled.

### Bookmark this link also and consider OWASP fundamentals any time you inte

https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html


## Additional Questions

### Looking ahead at this module’s course schedule, What do you look forward to learning?

I'm looking forward to see how linked list do infact help us understand the application of authentication.


### What are your learning goals after reading and reviewing the class README?

My learning goal is to essentially be comfortable with linked lists and authentication. I do not feel comfortable with either.

[Back to Home](https://zusolaris.github.io/reading-notes/)