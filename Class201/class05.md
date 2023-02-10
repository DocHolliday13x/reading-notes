# Class 05 Reading Assignment

## HTML Media

1. What is a real world use case for the alt attribute being used in a website?
It is supposed to be a textual description of the image, for use in situations where the image cannot be seen/displayed or takes a long time to render because of slow internet connection. This is handy for visually impaired users who use a screen reader to read the web out to them. Or when a browser doesn't support the image type.

2. How can you improve accessibility of images in an HTML document?
By adding effective alternative text (alt text) to your images.

3. Provide an example of when the figure element would be usefule in an HTML document:
When you need to provide a semantic container for figures, and to clearly link the figure to the caption.

4. Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community:
GIFs are useful for simple animations that don't need to scale very much, and the quality is typically low.
SVGs are ideal for diagrams, icons and other images which can be accurately drawn at any size, and when rendering size may vary.

5. What image type would you use to display a screenshot on your website and why?
You should use a lossless format like PNG or WebP, with a fallback like PNG or JPEG. This is your best bet if there isn't any text in the screenshot, as text can become fuzzy and unclear under lossy compression.


## Learn CSS

1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge:
Foreground colors are the colors you should see on the screen BEFORE background colors. Therefore, foreground color is the color that an element appears in. 
ex. colored text (foreground) on a colored background.

2. Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?
I would use CSS to specify colors for rendering elements. I could apply a color pallete of my friend's choice and apply those colors to any elements that friend desires, such as text, boxes and borders.

3. What should you consider when choosing fonts for an HTML document?
The browser will only apply a font if it is available on the machine the website is being accessed on, otherwise it will just display the browser's default font. So one should consider using web safe fonts.

4. What do font-size, font-weight, and font-style do to HTML text elements?
   1. font-size: sets the size of the font using CSS values and units
   2. font-weight: used to set how bold the text is
   3. font-style: used to turn italic text on or off

5. Describe two ways you could add spacing around the characters displayed in an h1 element:
   1. letter-spacing: you could set the spacing between letters to improve legibility of dense fonts.
   2. word-spacing: set the spacing between words to obtain a certain look


   ## Things I Want to Know More About

   I've already admitted several times that CSS is not one of my strengths. But the more I read the MDN on CSS, I pick up a little more knowledge each reading. The real learning will occur when I implement these lessons in my CSS code itself where I can play with these and visually see what they do.