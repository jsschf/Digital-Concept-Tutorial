# HTML Elements
Let's have a look at the previous HTML document:

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Intro to HTML</title>
    </head>
    <body>
        <h1>What is HTML?</h1>
        <p>This my introduction to learning HTML</p>
    </body>
</html>
```
- An HTML element is defined by a start tag, some content, and an end tag. Elements are the structure that make up an HTML document.
- Above you will see a "title" element. That element has a start tag `<title>`, content "Intro to HTML", and end tag `</title>`. Everything from the start tag to the end tag is an HTML element.
- Most elements follow this pattern, but some elements have no content and/or end tags, like the `<br>` tag.

Let's break down the elements in our HTML document:
- `<!DOCTYPE html>`
  - This element is necessary to notify the browser that the file is an HTML document.
  - It has no end tag.
- `<html>`
  - This element is the root of the HTML page.
  - All other elements go between the start and end tags.
- `<head>`
  - This element is a containter for metadata about the HTML page.
  - Things like defining the charset, linking stylesheets, and defining the title go inside this element.
- `<title>`
  - This element defines the document's title.
  - The title will be shown in the browser's tab.
- `<body>`
  - This element contains all the content that will be displayed in a web page.
- `<h1>`
  - This is a heading tag.
  - The size and importance of the heading can be changed by changing the number in the tag. `<h1>` being the most important and `<h6>` being the least important.
    - ex. `<h1>`, `<h2>`, ... `<h6>`.
- `<p>`
  - This a paragraph tag.
  - Paragraph tags are uses to display text.

To look learn about HTML Attributes, click "Next"

## [Previous](html_intro.md) | [Home](README.md) | [Next](html_attributes.md)