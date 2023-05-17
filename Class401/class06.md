# Class 6 Reading: Authentication

## Resources

- [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)
- [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)
- [OWASP Auth CheatSheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)
- [bcrypt docs](https://www.npmjs.com/package/bcrypt)
- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-06/)

## Securing Passwords

1. Explain to a non-technical friend how you would safely hash and store a password.

    - I would use bcrypt to hash the password and then store the hash in a database.

2. What is Bcrypt?

    - Bcrypt is a password hashing function.

3. Why might you use something like Bcrypt?

    - Bcrypt is a password hashing function that is slow and intentionally computationally expensive. This makes it more difficult for hackers to crack passwords.

## Basic Auth

1. What is Basic Authentication?

    - Basic Authentication is a method for a HTTP user agent to provide a user name and password when making a request.

2. What properties are necessary in the header of a Basic Authentication request?

    - The Authorization header is necessary in a Basic Authentication request.

3. How are `username:password` in Basic Auth encoded?

    - `username:password` in Basic Auth is encoded using base64.

## OWASP Auth Cheat Sheet

1. Define the authentication process to a non-technical recruiter.

    - The authentication process is the process of verifying the identity of a user.

2. How should your error messaging respond (both HTTP and HTML)? Why?

    - Error messages should be vague and not reveal too much information. This is to prevent hackers from gaining information that could be used to exploit the system.

3. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

### Bookmark and Review

- [bcrypt docs](https://www.npmjs.com/package/bcrypt)

### Additional Questions

1. Looking ahead at this module's course schedule, what do you look forward to learning?

    - I look forward to learning more about authentication and authorization.

2. What are your learning goals after reading and reviewing the class README?

    - My learning goals are to understand authentication and authorization better, and how to implement authentication and authorization in my projects. I would like to gain a stronger understanding of best security practices for full stack applications.

#### Things I Want to Know More About

1. I want to know more about bcrypt and how it works. Digital security is critical for full stack applications, and I want to know more about how to implement it.

![KickstartMyHeart](https://media.giphy.com/media/xvvpqYZHzH2SqScLCa/giphy-downsized-large.gif)
