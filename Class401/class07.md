# Class 7 Reading: Bearer Authorization

## Resources

- [Intro to JWT](https://jwt.io/introduction/)
- [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)
- [JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)
- [npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)
- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-07/)

## Intro to JWT

1. What is JSON Web Token?
    - JSON Web Token (JWT) is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

2. When should we use JSON Web Tokens?
    - Authorization
    - Information Exchange

3. Claims are expected in which structural component of a JWT?
    - Claims are expected in the payload of a JWT.

## Are JWTs Secure?

1. If I get a JWT and I can decode the payload, how can we call that secure?
    - JWTs are not secure if the payload is not encrypted. However, if the payload is encrypted, then JWTs are secure.

2. If sending a JWT, what must a sender and receiver both know? Hint: it's in the signature.
    - The sender and receiver must both know the secret key.

3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
    - The secret key is used to encrypt the payload. The encrypted payload is then sent to the receiver. The receiver then uses the secret key to decrypt the payload.

## JWTs Explained

1. Why use JWT?
    - JWTs are used for authorization and information exchange.

2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
    - JWTs are compact and self-contained. This means that they are easy to send and receive. They are also easy to verify.

3. What are the three components (the structure) of a JWT signature?
    - The three components of a JWT signature are header, payload, and signature.

### Bookmark and Review

- [npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)

### Reflection

1. What are your learning goals after reading and reviewing the class README?
    - My learning goals after reading and reviewing the class README are to learn more about JWTs and how to use them.

#### Things I Would Like to Know More About

- ![tokens](https://media.giphy.com/media/GNvWw0pDL6QRW/giphy.gif)
