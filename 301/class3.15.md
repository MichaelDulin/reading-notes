# Class 3.15 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 15**
- [What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)
- [Authorization and Authentication flows](https://auth0.com/docs/get-started/authentication-and-authorization-flow)


**What is OAuth**
1. What is OAuth?
  - Open-standard authorization pprotocol or framework that describes how unrelated servers and services allow authenticated access to their assets securely
2. Give an example of what using OAuth would look like.
  - When you log into a website and are given several ways to verify autherization using other security protocol API's
3. How does OAuth work? What are the steps that it takes to authenticate the user?
  - The first website asks the second site to provide a one-time security token, which if authorized will allow access
4. What is OpenID?
  - OpenID: Authentication
  - OAuth: authorization

  
**Authorization and Authentication flows**
1. What is the difference between authorization and authentication?
  - Authentication is done by OAuth, which then gets authorization to access protected resources
2. What is Authorization Code Flow?
  - Exchanging authorization code for a token
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
  - Adds an additional level of security
4. What is Implicit Flow with Form Post?
  - Intended for public clients which are unable to securely store client secrets
5. What is Client Credentials Flow?
  - Machine to machine (back-end), system authenticates the app rather than the user
6. What is Device Authorization Flow?
  - Rather than authenticating the user directly, device asks user to use a link to autherize device.
7. What is Resource Owner Password Flow?
  - (NOT RECOMMENDED) Can provide a form for users to input their credentials



## Things I want to know more about
