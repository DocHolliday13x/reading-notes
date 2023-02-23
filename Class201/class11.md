# Class 11 Reading Assignment

## Video and Audio Content

[Video and Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

1. Explain how the ability to use video and audio on the web has evolved since the early 2000's.
   * The first influx of online video and audio were made possible by plugin-based tecnologies like Flash and Silverlight, both os which had security and accessibility issues and are also now obsolete. We now use HTML elements <video> and <audio> along with JavaScript APIs.

2. Describe the use of the src and controls attributes in the <video> element:
   * the src attribute contains a path to the video you want to embed. the controls attribute allows people to have control, so you either need this or to build your interface using JavaScript APIs.

3. Why is it important to have fallback content inside the <video> element?
   * It can be displayed if the browser does not support the video element, allowing us to provide a fallback for older browsers.

4. Write a very short story where <audio> and <video> are characters:
   * <audio> and <video> are just two totally human characters. <audio> is very loud, and <video> is very flashy. They lived in HTML town, and their parent elements got tired of them trying to one-up each other, so they made them work together and they ended up putting on quite a lovely presentation for everyone. Now they are best friends and do karate in the garage together.

## A Complete Guide to Grid

[Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

1. How does grid layout differ from flex?
   * flexbox was designed for layout in one dimension, like a row or column. Grid can be used for two dimensional layout, like rows AND columns.

2. Grid container, grid item, and grid line are a few important terms to understand when using grid. Please describe these terms in a few sentences:
   * Grid container: the element on which display: grid is applied.
   * Grid item: the child element of the grid container.
   * Grid line: the dividing linea of the grid container that can be vertical, horizontal, ot both.

## Responsive Images

[Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
   * they will work well on devices with widely different screen sizes, resolutions, and other such features.

2. Define the following <img> attributes srcset and sizes. Write an example of how they are used.
   * srcset: defines the set of images that we will allow the browser to choose between, and what size each image should be.
   * sizes: defines the set of media conditions and indicates wwhat image size would be best to choose, when certain media conditions are true.

3. How is srcset more helpful for responsive images than CSS or JavaScript?
   * When the browser starts to load a page, it starts to download (preload) any images before the main parser has started to load and interpret the page's CSS and JavaScript. That mechanism is useful in general for reducing page load times, but it is not helpful for responsive images — hence the need to implement solutions like srcset.

## Bookmark and Review

[Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)
[Other Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)
