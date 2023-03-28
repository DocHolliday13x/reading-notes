# Class 12: CRUD

## Resources

* [Status Codes Based on REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
* [Build A REST API With Node.js, Express, & MongoDB - Video](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

### Reading Statement

Why this topic matters as it relates to the material I am studying:

### Status Codes Based on REST methods

1. In your own words, describe what each group of status code represents:
   * 100’s = informational codes - request recieved, server trying to comply
   * 200’s = success codes - request accepted.
   * 300’s = redirection codes - requested resource unavailable
   * 400’s = client error codes - invalid requests from client to server
   * 500’s = server error codes - servers unreachable

2. What is a status code 202? Accepted - Asynchronous processing of a request.

3. What is a status code 308? Permanent redirect - resource will be available at new URL.

4. What code would you use if an update didn’t return data to a client? 404 - Not Found

5. What code would you use if a resource used to exist but no longer does? 410 - Gone

6. What is the ‘Forbidden’ status code? 403 - the client has authorized or doesn't need to authorize itself, but still has no permissions to access the resource.

### Build a REST API with Node.js, Express, and MongoDB

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env? We will want to use something that is not our local host so we place it into our environmental variable.

2. What is middleware? A software that allows different applications to communicate with each other.

3. What does app.use(express.json()) do? Parses incoming JSON information.

4. What does the /:id mean in a route? Alllows us to have a parameter that will have access to everything typed after it.

5. What is the difference between PUT and PATCH? PUT updates everything every time something new is added, but PATCH allows the info to get partially updated based off of input recieved.

6. How do you make a default value in a schema? Create a variable so that we can set objects in the schema with default values, ie. in video: names, subscribersToChannel, and subscribeDate

7. What does a 500 error status code mean? Internal Server Error means that the server encountered an unexpected condition that prevented request fulfillment.

8. What is the difference between a status 200 and a status 201? 200 means that the request was successfully received and processed. 201 means that only the request was successfull, and resource created.

#### Things I Would Like to Know More About

1. I want to get as comfortable building a REST API as the guy in the video is.
