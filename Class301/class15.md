# Class 15 Reading: Authentication

## Resources

* [What is OAuth?](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

* [Authentication and Authorization Flows](https://auth0.com/docs/get-started/authentication-and-authorization-flow)

## Reading Statement

*Why this topic matters as it relates to the material I am studying:* This is an important topic because authorization and authentication protocols are an important aspect of many, if not all, of today's web applications. Learning how these two things operate and how to implement them into future applications that I design will prove to be an invaluable lesson.

### What is OAuth?

1. *What is OAuth?* OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization.

2. *Give an example of what using OAuth would look like.* The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website.

3. *How does OAuth work? What are the steps that it takes to authenticate the user?* Let’s assume a user has already signed into one website or service (OAuth only works using HTTPS). The user then initiates a feature/transaction that needs to access another unrelated site or service. The following  simplified steps happen:

   1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
   2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
   3. The first site gives this token and secret to the initiating user’s client software.
   4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
   5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
   6. The user approves (or their software silently approves) a particular transaction type at the first website.
   7. The user is given an approved access token (notice it’s no longer a request token).
   8. The user gives the approved access token to the first website.
   9. The first website gives the access token to the second website as proof of authentication on behalf of the user.
   10. The second website lets the first website access their site on behalf of the user.
   11. The user sees a successfully completed transaction occurring.
   12. OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).

4. *What is OpenID?* OpenID is about authentication. It's for humans logging into machines whereas OAuth is for machines logging into machines on behalf of humans. The idea, in the early days of Web 2.0, was that rather than having multiple logins for multiple websites, OpenID would serve as a single sign-in, vouching for the identities of users.

### Authorization and Authenctication Flows

1. *What is the difference between authorization and authentication?* Authentication is the process of verifying who a user is while authorization is the process of verifying what they have access to.
! [AuthenticationVsAuthorization1](img/authenticationVsAuthorization1.png)

2. *What is Authorization Code Flow?* The Authorization code flow is the user clicking login, Auth0's SDK redirects the user to the authorization prompt, user authenticates using one of the login options and consent to permissions of the Auth0, the authentication redirects the user back to application, the code goes through the authentication server, the server verifies the code and client ID secret, then ID token and access are used and the API responds with the data.
! [AuthenticationVsAuthorization2](img/authenticationVsAuthorization2.png)

3. *What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?* PKCE authentication is very similar to the steps above however utilizes code challenge and code verifier.
! [AuthenticationVsAuthorization3](img/authenticationVsAuthorization3.png)

4. *What is Implicit Flow with Form Post?* The implicit flow starts with user clicking login, the credential request and response mode goes to authorization, then redirect to login and authorization prompt, authenticate and consent, and then ID token is sent to user.
! [AuthenticationVsAuthorization4](img/authenticationVsAuthorization4.png)

5. *What is Client Credentials Flow?* The client credentials starts with application authenticating with server using Client ID and Client Secret, the id and secret get validated and responds with an access token, user data is requested with access token, then API responds with data.
! [AuthenticationVsAuthorization5](img/authenticationVsAuthorization5.png)

6. *What is Device Authorization Flow?* The device authorization flow starts with the device app starting, authorization request goes to the OAuth, device code + user code + verification url, the device asks the user to interact in some way, a poll occurs to get the AuthO authorization for access token, the browser user flow kicks in now with the user code being entered and redirects to login with consent prompt, the user authenticates using a login option, the device is then authorized access to the API, then the device can use the access token to call the API for information about the user and the API responds with the data.
! [AuthenticationVsAuthorization6](img/authenticationVsAuthorization6.png)

7. *What is Resource Owner Password Flow?* The resource owner password flow begins with the user click login with their application, application forwards user credentials to AuthO server, the server validates credentials and responds with an access token, the application can then use the access token to call an API to get information about the user and the API responds with requested data.
! [AuthenticationVsAuthorization7](img/authenticationVsAuthorization7.png)

### Bookmark and Review

* [AuthO for Single Page Apps](https://auth0.com/docs/libraries/auth0-react)

### Things I Would Like to Know More About

1. The vulnerablilities with OAuth and OpenID.