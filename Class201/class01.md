# Class 01 Reading Assignment

## Getting Started

1. HTTP,
   What does that mean to me?
   A defined language for my PC
   To access webpages I can see

2. HTML parsed first, browser then recognizes any <link> and <script> elements. Browser sends request back to the server, then parses CSS and JavaScript. Browser generates in-memory DOM tree from parsed HTML, generates in-memory CSSOM structure from parsed CSS, then compiles and executes parsed JavaScript. As the browser builds DOM tree and applies styles from CSSOM tree and executes JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can then interact with it.

3. You can use google images, then click on tools, and check Creative Commons Licenses. 

4. String = 'abcdefg'
   Number = 5
   A string will be wrapped in "" or '' whereas a number will not be.

5. Variables are containers that store values (data types). Variables are necessary, and if the values could not change then you wouldn't be able to do anything dynamic.

## Intro to HTML

1. An HTML attribute contains extra info about the element that won't appear in the content. It should have a space between it and the element name, the attribute name, followed by an equal sign, an attribute value wrapped with opening and closing quote marks.

2. Anatomy of HTML element: Opening Tag, Content, Closing Tag.

3. Difference between article and section element tags: <article> encloses a block of related content that makes sense on its own without the rest of the page. A <section> is similar, but is more for grouping together a single part of the page that constitutes one single piece of functionality, or a theme. You can break up articles into different sections and vice versa. 

4. Elements of a typical website:
   * header
   * navigation bar
   * main content
   * sidebar
   * footer

5. The description meta and title element content are used in the search result.

6. Metadata can be used to set the language of a page, add author information, and a description of the page itself. 

## Resources

* [How The Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
* [What Will Your Website Look Like](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)
* [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

### How The Web Works

Client --> Request --> Server --
                                |
         Client <-- Response <--

Clients are web user's internet connected devices and web accessing software on those devices. Servers are computers that store webpages, sites, or applications. When a client wants to access a webpage, a copy of the webpage is downloaded from the server onto the client machine to be displayed on the user's web browser.

Additional Basics:

* Internet Connnection: Allows you to send and recieve data on the web.
* TCP/IP: Transmission Control Protocol / Internet Protocol - communication protocols that define how data travels across the internet.
* DNS: Domain Name System - address book for websites.
* HTTP: Hypertext Transfer Protocol - application protocol that defines a language for clients and servers to speak to each other.
* Component Files: Code Files - Websites are built primarily from HTML, CSS and JavaScript. Assets - Collective name for other elements of a website, like images, music, video and PDFs.

The order in which component files are parsed:

* HTML parsed first, browser then recognizes any <link> and <script> elements.
* Browser sends request back to the server, then parses CSS and JavaScript.
* Browser generates in-memory DOM tree from parsed HTML, generates in-memory CSSOM structure from parsed CSS, then compiles and executes parsed JavaScript.
* As the browser builds DOM tree and applies styles from CSSOM tree and executes JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can then interact with it.

### What Will Your Website Look Like?

Plan First!

* What is your website about?
* What information are you trying to present?
* What do you want your website to look like?

You can begin with a hand drawn sketch or wireframe. Then you can choose which assets you would like to appear on your page, such as text, font, theme color, and images.

### JavaScript Basics

JavaScript = programming language that can add interactivity to a website. 

How does JavaScript work?
Some core features of JavaScript:

* Variables: containers that store values.
  * Data Types of Variables:
    1. String
    2. Number
    3. Boolean
    4. Array
    5. Object

* Operators

* Conditionals

* Functions


