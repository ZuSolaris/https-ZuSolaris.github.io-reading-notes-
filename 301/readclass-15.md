# Reading #15 :D



## What is OAuth

**What is OAuth?**

O auth is an open-standard authorization protocal or framework that describes how unrelated servers and services can allow authention. Without sharing access to their intial related credntials.

**Give an example of what using OAuth would look like.**

Using Google or GitHub to sign in via a different website.

**How does OAuth work? What are the steps that it takes to authenticate the user?**

Steps according to **https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html**

The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.

The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.

The first site gives this token and secret to the initiating user’s client software.

The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).

If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.

The user approves (or their software silently approves) a particular transaction type at the first website.

The user is given an approved access token (notice it’s no longer a request token).

The user gives the approved access token to the first website.

The first website gives the access token to the second website as proof of authentication on behalf of the user.

he second website lets the first website access their site on behalf of the user.

The user sees a successfully completed transaction occurring.

OAuth is not the first authentication/authorization system to work this way on behalf of the end-user.

**What is OpenID?**

It was a single sign in made for a multitude of different websites! But it became obsolete and shadowed Facebook connect. Then OpenID connect became a thing and it an authentication layer for OAuth.

## Authorization and Authentication flows

**What is the difference between authorization and authentication?**

OAuth is authorization its the act of the software logging on for you while Open ID verifies and ensures that you are really the user.

**What is Authorization Code Flow?**

Your app must be server-side because during this exchange, you must also pass along your application's Client Secret, which must always be kept secure, and you will have to store it in your client.

**What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?**

It is an authorization code flow that introduces a secret by calling applications that are verified by the auth server. This is the where the code verifier lives. It also hides this key with a code challenge this makes it where they only get the authorization code and not the code verifier. Its extra layers of security basically.

**What is Implicit Flow with Form Post?**

It was made for Public Clients, or applications which are unable to securely store Client Secrets. This allows ID tokens to perform user authentication.

**What is Client Credentials Flow?**

With machine-to-machine (M2M) applications, such as CLIs, daemons, or services running on your back-end, the system authenticates and authorizes the app rather than a user.

**What is Device Authorization Flow?**

This is when the service utilized a device to provide authorization.

**What is Resource Owner Password Flow?**

When an applications requests that users provide credentials (username and password), typically using an interactive form. A typical user name and pass word form.

[Back to Home](https://zusolaris.github.io/reading-notes/)