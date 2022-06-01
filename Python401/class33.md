# Authentication & Production Server

## Introduction to JSON Web Tokens

- JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. 
- JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.
- Signed tokens can verify the integrity of the claims contained within it, while encrypted tokens hide those claims from other parties.
- Used for authorization and information exchange
- In its compact form, JSON Web Tokens consist of three parts separated by dots (.), which are:
    - Header
    - Payload
    - Signature

## JWT Authentication with Django REST

- The JWT is acquired by exchanging an username + password for an access token and an refresh token.
- The access token is usually short-lived (expires in 5 min or so, can be customized though).
- The refresh token lives a little bit longer (expires in 24 hours, also customizable). It is comparable to an authentication session. After it expires, you need a full login with username + password again.

## Django Runserver

- the server started with runserver is not guaranteed to be performant (it’s very slow), and it hasn’t been built with security concerns in mind
- Your Django app does not actually run as you would think a server would - waiting for requests and reacting to them.
- use a production-ready web server like Nginx, and let your app be handled by a WSGI application server like Gunicorn.

### Resources 
- https://jwt.io/introduction/
- https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html 
- https://vsupalov.com/django-runserver-in-production/
