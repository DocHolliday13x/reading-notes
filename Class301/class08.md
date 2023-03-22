# Class 08 Reading Assignment: API's

## Resources

* [API Best Design Practices](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)
* [RegExr](https://regexr.com/)
* [RegEx Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
* [Regex 101](https://regex101.com/)

### Reading Statement

Why this topic matters as it relates to the material I am studying: We use web APIs in our labs. Knowing the codes they throw out is going to be extremely useful for debugging purposes, as I found out tonight during the 10 hours I spent on lab 07. Fun times, man.

### API Design Best Practices

1. What does REST stand for?

   * Representational State Transfer

2. REST APIs are designed around a _______.

   * resource, which is any kind of of object, data, or service that can be accessed by a client.

3. What is an identifier of a resource? Give an example:

   * a URI that uniquely identifies a resource.

4. What are the most common HTTP verbs?

   * GET, POST, PUT, DELETE

5. What should the URIs be based on?

   * Inidividual resources

6. Give an example of a good URI:

   * https://adventure-works.com/orders // Good

   * https://adventure-works.com/create-order // Avoid

7. What does it mean to have a 'chatty' web API? Is this a good or a bad thing?

   * requires consumer to make tremendous amount of distinct API calls to get needed information about a resource. It's not good.

8. What status code does a successful GET request return?

   * HTTP status code: 200 (OK)

9. What status code does an unsuccessful GET request return?

   * HTTP status code: 204 (No Content)

10. What status code does a successful POST request return?

    * HTTP status code: 201 (Created)

11. What status code does a successful DELETE request return?

    * HTTP status code: 204 (No Content)

#### Bookmark and Review

* [RegExr](https://regexr.com/)
* [RegEx Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
* [Regex 101](https://regex101.com/)

#### Thing I Would Like to Know More About

1. API's have a lot of different codes, but I feel like if I study them for a bit, I could memorize the important ones, or at least the ones that I will be using regularly.
