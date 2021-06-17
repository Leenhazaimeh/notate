# Authentication
What is OAuth?
OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.

1. Give an example of what using OAuth would look like.
loggin in to a website using another webite's that you already have an account authintecated in it authentication.

2. How does OAuth work? What are the steps that it takes to authenticate the user?

The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.




The first site gives this token and secret to the initiating user’s client software.
The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
If not already authenticated to the authorization provider, the client may be asked to authenticate.



 After authentication, the client is asked to approve the authorization transaction to the second website.
The user approves (or their software silently approves) a particular transaction type at the first website.
The user is given an approved access token (notice it’s no longer a request token).
The user gives the approved access token to the first website.
The first website gives the access token to the second website as proof of authentication on behalf of the user.
The second website lets the first website access their site on behalf of the user.




5. What is OpenID?
OpenID is about authentication.
What is the difference between authorization and authentication?
authoriztion is to provide access to someone who is already authenticated while authentication means for someone to prove the identey they present.


6. What is Authorization Code Flow?
Because regular web apps are server-side apps where the source code is not publicly exposed, they can use the Authorization Code Flow, which exchanges an Authorization Code for a token.


7. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange.
8. What is Implicit Flow with Form Post?
Implicit Flow with Form Post flow uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates.


9. What is Client Credentials Flow?
machine to machine authentication.
What is Device Authorization Flow?
With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device.


10. What is Resource Owner Password Flow?
highly-trusted applications can use the Resource Owner Password Flow, which requests that users provide credentials (username and password), typically using an interactive form. The Resource Owner Password Flow should only be used when redirect-based flows (like the Authorization Code Flow) cannot be used.