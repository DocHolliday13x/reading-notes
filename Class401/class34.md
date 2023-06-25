# Class 34 Reading: API Integration

## Resources

- [Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)
- [Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

## Review API Server Build

1. Explain the different between a query string parameter and a path parameter. When would you use each?

    - A query string parameter is a key-value pair that is appended to the end of a URL. A query string parameter is used to filter the results of a request. A path parameter is a variable that is part of a URL path. A path parameter is used to identify a specific resource.

2. What would our API URL with a path id parameter be given the following information:

   1. Domain: `http://our-site.com`
   2. v3
   3. Model Name: `stuff`
   4. Model ID: `things`

    - `http://our-site.com/api/v3/stuff/things`

3. We have created a dynamic API with an "interface". Describe how that interface works to a non-technical friend.

    - The interface is a set of endpoints that can be used to interact with the API. Each endpoint is a URL that can be used to perform a specific action. For example, an endpoint might be used to create a new resource, or to retrieve a list of resources.

## Review Auth Server Build

1. Describe how you would use middleware to implement basic and bearer Auth.

    - Basic Auth is implemented by using the `express-basic-auth` middleware. The middleware is added to the server, and the middleware is configured with a username and password. When a request is made to a protected route, the middleware will check the request for a username and password. If the username and password are valid, the request will be allowed to continue. If the username and password are invalid, the request will be rejected.

    - Bearer Auth is implemented by using the `express-bearer-auth` middleware. The middleware is added to the server, and the middleware is configured with a secret. When a request is made to a protected route, the middleware will check the request for a bearer token. If the bearer token is valid, the request will be allowed to continue. If the bearer token is invalid, the request will be rejected.

2. Describe the handshake necessary to implement OAuth.

    - OAuth is implemented by using the `express-oauth-server` middleware. The middleware is added to the server, and the middleware is configured with a model. When a request is made to a protected route, the middleware will check the request for an access token. If the access token is valid, the request will be allowed to continue. If the access token is invalid, the request will be rejected.

3. Describe how role based access control works to a non-technical friend.

    - Role based access control is implemented by using the `access-control` middleware. The middleware is added to the server, and the middleware is configured with a set of roles. When a request is made to a protected route, the middleware will check the request for a role. If the role is valid, the request will be allowed to continue. If the role is invalid, the request will be rejected.

### Things I Want to Know More About

1. I need to practice more with OAuth. I understand the basic concepts, but I need to practice implementing it.

![GIF](https://media.giphy.com/media/WdPfyBVZzIS3GrNWAu/giphy.gif)
