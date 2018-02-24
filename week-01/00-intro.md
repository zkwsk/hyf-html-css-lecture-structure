# Hello new class!

## Setup

* does everybody have slack - write hello
* does everybody have github account
* does everybody have VScode or any other code editor

## Review of week 00 homework:

* ask if everybody read the chapters from the frontend handbook
* ask the questions from the bullet points mentioned in the `Week0/Readme.md` (explain in own words)
* ask what is ARIA (explain in own words)

## Structure of a lecture

### HTML intro

_make the examples brutally simplistic_

* create [barebones HTML document](http://www.coreservlets.com/html5-tutorial/basic-html5-document.html)
* create hello world
* get to know the text editor (closing tags, indentation etc.)
    * walk through special characters - does it work for everybody? - give people 3 minutes
    * page of most commont special charaters: type them in: `!!@#$%^&*()}{|"?><>}`
* intro to DOM (it exists, there's a hierarchy of elements)
* illustrate hierarchy with `<p><i></i></p>`
* mention [MDN](https://developer.mozilla.org/en-US/docs/) as a good source of information look for `<p>`
* review links how to declare a link and what does it do `<a href="#"></a>`
* it is important to understand that we're essentially throwing a bunch of text at a browser, search engine or a screen reader - it has to be delivered properly (by using the proper tags)
* content related elements `<article> <h1> <p> <ul> <img>`
* write two articles and make internal links - introdcue `id`

### CSS intro

* inline CSS - change the font color on all headings and paragraphs
* explain it's not practical because you need to repeat stuff milion times
* link CSS (understand that you can reference a file in HTML)
* set `p { font-size: 20px }`
* intoduce `class` - refactor the inlne color declaration
* check the code with validator
* peseudo elements if needed
* tables?

### Code a layout

* take a layout and code it live with students:

    * illustrate: Naming things, how to structure a CSS file [wikipedia](https://en.wikipedia.org/wiki/North_Ronaldsay_sheep) or [BBC](http://www.bbc.com/earth/story/20160126-the-monkeys-that-sailed-across-the-atlantic-to-south-america) can be used to illustrate the use of semantic elements)

* aria (semantic HTML, forms if we get there)

## Code

### Minimal HTML

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>Hello World!</title>
  <link href="css/some-stylesheet.css" rel="stylesheet" />
</head>

<body>
</body>

</html>
```

### Example of simple content section (from the page mentioned)

```HTML
<article>
  <header>
    <h1>The monkeys sailed accross the Atlantic</h1>
    <h2>Monkeys suddenly appeared in South America about 40 million years ago.</h2>
    <address>Josh Gabbatiss</address>
    <p><time datetime="2016-01-26">26 January 2016</time></p>
  </header>
  <p>Earlier transatlantic travellers may have beaten him to it, of course: the <a href="http://www.smithsonianmag.com/history/the-vikings-a-memorable-visit-to-america-98090935/?no-ist">Vikings</a> almost certainly made the crossing, and there are claims that the Egyptians and all manner of other groups did too.</p>
  <p>Midway through the Eocene, a crew of monkeys sailed the ocean, er, green.</p>
  <figure>
    <img src="http://ichef.bbci.co.uk/wwfeatures/wm/live/624_351/images/live/p0/3g/m7/p03gm72c.jpg" alt="monkey standing on the coast - looking grim" />
    <figcaption>Wet after a bit of a swim (Credit: Yury Barsukov/Alamy Stock Photo)</figcaption>
  </figure>
</article>
```

## Homework notes

* [link to the image](http://1.bp.blogspot.com/-TQiNTNxcfJg/ThsKEfccf1I/AAAAAAAAAR8/2i0-56tLzmc/s1600/desktop_landscape_wallpaper.jpg)
* fonts:
    * Serif: Times New Roman
    * Sans-serif: Arial
* colors:
    * #43948e
    * #594b3a
    * #000
