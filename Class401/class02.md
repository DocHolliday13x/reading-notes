# Class 2 Reading: Express, NPM, TDD, CI/CD

## Resources

- [Intro to NodeJS/Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)
- [What is NPM](https://docs.npmjs.com/about-npm)
- [What is TDD](https://www.agilealliance.org/glossary/tdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'tdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1))
- [CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)
- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-02/)

### An Introduction to NodeJS and Express

1. Explain middleware, answer as though I were a non-technical recruiter.

    - Middleware is a function that has access to the request and response objects. It can be used to modify the request or response objects, or to perform some other action. Middleware is executed in the order it is defined, so it is important to define middleware in the correct order.

2. Express is the most popular _________.

    - NodeJS framework. It is popular because it is easy to use and has a large ecosystem of plugins and middleware.

3. Express is "unopinionated". What does that mean?

    - Express is unopinionated, meaning that it does not have a set of rules or conventions that you must follow. It is up to you to decide how you want to structure your application.

4. What is a module and why is modularity useful to us as developers?

    - A module is a collection of code that can be used in other programs. Modularity is useful because it allows us to break our code into smaller pieces that are easier to maintain and reuse.

### What is NPM?

1. What version of npm are you running on your machine?
    - 9.6.4

2. What command would you type to install a library/package called 'jshint'?
    - `npm install jshint`

### What is TDD?

1. Explain why tests are important. Please explain as though I were your non-technical elder.
    - Tests are important because they help us to ensure that our code is working as expected. They also help us to catch bugs before they become a problem in production.

2. What are three expected benefits of testing?
    - Many teams report significant reductions in defect rates, at the cost of a moderate increase in initial development effort.
    - The same teams tend to report that these overheads are more than offset by a reduction in effort in projects’ final phases.
    - Although empirical research has so far failed to confirm this, veteran practitioners report that TDD leads to improved design qualities in the code, and more generally a higher degree of “internal” or technical quality, for instance improving the metrics of cohesion and coupling.

3. Name at least 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
    - Individual pitfalls:
        - Forgetting to run tests frequently.
        - Writing too many tests at once.
        - Writing tests that are too large or coarse-grained.
        - Writing overly trivial tests, for instance omitting assertions
        - Writing tests for trivial code, for instance accessors.
    - Team pitfalls:
        - Partial adoption: only a few devs on the team use TDD.
        - Poor maintenance fo the test suite - most commonly leading to a test suite with a prohibitively long running time.
        - Abandoned test suite (i.e. seldom or never run) - sometimes as a result of poor maintenance, sometimes as a result of team turnover.

### CI/CD

1. What are three benefits of Continous Integration?
    - Continuous integration helps to reduce the risk of integration problems.
    - It allows us to detect bugs early in the development cycle.
    - It helps to reduce the cost of integration.

2. What is the difference between Continous Delivery and Continous Deployment?
    - Continuous delivery is the process of automating the delivery of software to production. Continuous deployment is the process of automatically deploying software to production.

3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background.
    - GitHub is a web-based hosting service for version control using Git. It is used by developers to collaborate on projects and share code with each other.

### Bookmark and Review

- [nodeJS docs](https://nodejs.org/en/docs)
- [npm docs](https://docs.npmjs.com/)
- [express docs](https://expressjs.com/en/4x/api.html)
- [http status codes](https://www.restapitutorial.com/httpstatuscodes.html)
- [supertest](https://github.com/ladjs/supertest)

#### Things I Would Like to Know More About

- How to use supertest to test routes that require authentication.
