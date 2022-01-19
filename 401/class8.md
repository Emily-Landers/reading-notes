# Reading: Access Control (ACL)

- When is Basic Authorization used vs. Bearer Authorization?
    - The Bearer authentication scheme is dedicated to the authentication using a token and is described by the RFC6750. Even if this scheme comes from an OAuth2 specification, you can still use it in any other context where tokens are exchange between a client and a server.
- What does the JSON Web Token package do?
    - JWT (JSON Web Token) is an open standard (published in the RFC 7519) which defines a compact and self-contained method to encapsulate and share assertions (claims) about an entity (subject) between peers in a secure manner by using JSON objects.
- What considerations should we make when creating and storing a SECRET?
    - Differentiate Between Secrets and Identifiers.
    - Establish a Circle of Trust.
    - Gain Visibility into the Chain of Trust.
    - Encrypt Data Using a KMS.
    - Rotate Secrets Frequently.
    - Automate Password Creation.
    - Store Secrets Responsibly.
    - Detect Unauthorized Access.

### Document the following Vocabulary Terms

- encryption:a way of scrambling data so that only authorized parties can understand the information. In technical terms, it is the process of converting human-readable plaintext to incomprehensible text, also known as ciphertext.
- token: allows users to log into a service through data validation.
- bearer: an HTTP authentication scheme that involves security tokens called bearer tokens.
- secret: account passwords, OAuth tokens, SSL and SSH private keys.
- JSON Web Token: an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

- Which 3 things had you heard about previously and now have better clarity on?
    - JSON web tokens, SECRETs, Bearer authentication
- Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
    - Secrets, Bearer authentication, and encryption
- What are you most excited about trying to implement or see how it works?
    - Bearer authentication

- **Sources**
    - https://stackoverflow.com/questions/34013299/web-api-authentication-basic-vs-bearer 
    - https://www.bbva.com/en/json-web-tokens-jwt-how-to-use-them-safely/ 
    - https://thenewstack.io/8-best-practices-for-container-secrets-management/ 
    - https://jwt.io/introduction 
