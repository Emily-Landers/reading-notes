# Reading: Bearer Authorization

- What can you do with an authorization code?
    - authorize a user into a security-protected space.
- What can you do with an access token?
    - make API requests on behalf of a user.
- What’s a benefit of using OAuth instead of your own basic authentication?
    - It enables apps to obtain limited access (scopes) to a user's data without giving away a user's password.

- Document the following Vocabulary Terms

- Client ID: an identifier associated with an application that assists with client / server OAuth 2.0 authentication for client APIs.
- Client Secret:  a secret known only to your application and the authorization server. It protects your resources by only granting tokens to authorized requestors.
- Authentication Endpoint: a security mechanism designed to ensure that only authorized devices can connect to a given network, site or service.
- Access Token Endpoint: when apps make a request to get an access token for a user.
- API Endpoint: the point of entry in a communication channel when two systems are interacting. It refers to touchpoints of the communication between an API and a server. Basically a URL of a server or service.
- Authorization Code: a temporary code that the client will exchange for an access token. The code itself is obtained from the authorization server where the user gets a chance to see what the information the client is requesting, and approve or deny the request
- Access Token: an object encapsulating the security identity of a process or thread. A token is used to make security decisions and to store tamper-proof information about some system entity.

- Which 3 things had you heard about previously and now have better clarity on?
    - Authorization codes, access tokens, Client secret
- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    - Authentication endpoints, API endpoints, and Client secrets
- What are you most excited about trying to implement or see how it works?
    - Client secrets

- **Source**
    - https://developer.okta.com/blog/2017/06/21/what-the-heck-is-oauth#:~:text=It%20enables%20apps%20to%20obtain,apps%2C%20and%20consoles%2FTVs.
    - https://www.investopedia.com/terms/a/authorization-code.asp#:~:text=An%20authorization%20code%20is%20an,into%20a%20security%2Dprotected%20space.
    - https://www.oauth.com/oauth2-servers/access-tokens/#:~:text=Access%20tokens%20are%20the%20thing,parts%20of%20a%20user's%20data.