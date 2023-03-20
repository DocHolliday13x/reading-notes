# Class 07 Reading Assignment: REST

## Resources

* [What Google Learned From Its Quest to Build the Perfect Team](https://www.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.html)
* [How I explained REST to my brother](https://gist.github.com/brookr/5977550)
* [Geocoding API](https://locationiq.com/)
* [Weather Bit API](https://www.weatherbit.io/)
* [Yelp API Docs](https://docs.developer.yelp.com/reference/v3_business_search)
* [The Movie DB API Docs](https://developers.themoviedb.org/3/getting-started/introduction)

### Reading Statement

Why this topic matters as it relates to the material I am studying: This material is a great representation of how REST works and how APIs solve a lot of the issues we had with systems communicating with one another in the past. I don't fully understand all of it, but it's a step in the right direction.

### How I Explained REST to My Brother

1. Who is Roy Fielding?

   * He is the developer of the first web servers that sent documents across the internet (HTTP).

2. Why don't the techniques that we use in this class work well when we need to be able to talk to all of the machines in the world?

3. What is the HTTP protocol that Fielding and his friends created?

   * It describes the location of something from anywhere in the world, like the GPS coordinates for information. It's a general purpose protocol for applying verbs to nouns.

4. What does a GET do?

   * it's all about applying verbs to to nouns. When you go to a web page, the browser does an HTTP GET on the URL you typed in and comes back a web page. Web pages usually have images. Those are separate resources. The web page just specifies the URLs to the images and the browser goes and does more GETs using the HTTP protocol on them until all the resources are obtained and the web page is displayed. Very different kinds of nouns can be treated the same. Whether the noun is an image, text, video, an mp3, a slideshow, whatever. We can GET all of those things the same way given a URL.

5. What does a POST do?

   * When one system wants to add something to another system.

6. What does a PUT do?

   * If a system wants to replace something in another system.

7. What does PATCH do?

   * If a system wants to do a partial update of another system.

### API Keys

1. Geocoding API - Did you get your API key?

2. Weather Bit API - Did you get your API key?

3. Yelp API - Did you get your API key?

4. The Movie DB API Docs - Did you get your API key?

#### Things I Would Like to Know More About

1. 
