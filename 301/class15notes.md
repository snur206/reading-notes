# [Class 15 Reading Notes](https://github.com/snur206/reading-notes/blob/main/301/class15notes.md)

This topic matters because it is discussing a new topics in OAuth and authorization.

## What is OAuth

OAuth is is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential or a secure, third-party, user-agent, delegated authorization.

Logging into a website from the website's login service. 

OAuth works by the user  initiates a feature/transaction that needs to access another unrelated site or service. The steps:

- The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.

- The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.

- The first site gives this token and secret to the initiating user’s client software.

- The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).

- If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.

- The user approves (or their software silently approves) a particular transaction type at the first website.

- The user is given an approved access token (notice it’s no longer a request token).

- The user gives the approved access token to the first website.

- The first website gives the access token to the second website as proof of authentication on behalf of the user.

- The second website lets the first website access their site on behalf of the user.

- The user sees a successfully completed transaction occurring.

- OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).

OpenID is a security technology and is about authentication.

## Authorization and Authentication flows

The difference between authorization and authentication is that authentication is verifying the user and authorization is verifying what they have access to.

Authorization Code Flow exchanges an Authorization Code for a token.

Authorization Code Flow with Proof Key for Code Exchange (PKCE) is additional security with special challenges.  

Implicit Flow with Form Post is  Public Clients or applications which are unable to securely store Client Secrets. 

Client Credentials Flow is when M2M uses when the system authenticates and authorizes the app rather than a user.

Device Authorization Flow asks the user to go to a link on their computer or smartphone and authorize the device

Resource Owner Password Flow requests that the user provides credentials like username and password using an interactive form.

## Things I want to know more about

Authorization
