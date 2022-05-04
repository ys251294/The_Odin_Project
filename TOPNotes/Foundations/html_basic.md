# Chapter: Introduction to HTML & CSS

## HTML
- It is the raw data that a webpage is built out of.
- It is fundamental building block.
- It create structure for webpage.
- It put info info on webpage.
- Control the layout of content.

## CSS
- It is what adds style to these plain elements of HTML.
- It gives information color, changes the font, and makes it look great.
- It targets various screen sizes to make webpages responsive.
- It handles the "look and feel" of webpage.


# Elements and Tags
- Almost all elements on an HTML are just pieces of content wrapped in opening and closing HTML tags.
    - `<p> ipsum lorem </p>`
- HTML elements that do not have closing tag are known as empty elements.
    - `<img src="" alt="alt text">`

# HTML Boilerplate
**Boilerplate**: It is same basic structure that needs to be in place before anything useful can be done.

## Steps:
1. The DOCTYPE
    - It's purpose is to tell browser what version of HTML it should use to render the document.
    - `<!DOCTYPE html>` for latest html5.
2. HTML Element
    - It is root element of document.
    - `<html lang="en">` ------- other elements ----- `</html>`
    - `lang` specifies language if text entered int that element.
    - `lang` attribute is primarily used for improving the accessibility of the webpage.
3. Head Element
    - Put important meta information about our webpage and stuff required for webpages to render correctly in browser.
    - Should **not** use any element that display content onn the webpage.
4. Charset meta element
    - It is used in Head Element
    - It ensure that webpage will display special symbols and characters from different languages correctly.
    - `<meta charset="utf-8">`
5. Title Element
    - It is used to give human readable title to webpage.
    - `<title>This is a title</title>`
6. Body Element
    - This is where all the content will be displayed to users will go such as text, links, img, lists, & so on.
    - `<body>    lorem ipsum    </body>`


## Working with text
1. paragraph:  `<p>` lorem ipsum `</p>`
2. Headings: `<h1>` Heading 1 `</h1>` &emsp; &emsp; &emsp; Biggest <br/> &emsp; &emsp; &emsp; &emsp; &emsp;| &emsp; &emsp; &emsp; &emsp; &emsp;&emsp; | <br />&emsp; &emsp; &emsp; &emsp;`<h6>` Heading 6 `</h6>` &emsp; &emsp; &emsp; Smallest
3. Bold: `<strong>` Bold `</strong>`
4. Italic: `<em>` Italic `<em>`

- HTML allow nesting of elements with parent-child relationship.
- HTML comments are written by enclosing comment with `<!--` and `-->` tags.

## List:
- all `<ul>, <ol>, <li>` are non-empty tags.
- `<ul>` unordered list where order does not matter.
- `<ol>` ordered list where order does matter.
    - `<li>` list item tag to add items in ordered or unordered list.

## Links & Images:
1. Links: 
    - Link is used to create link with anothers webpage or section in HTML, we use anchor `<a>` element.
    - `<a>` Click me '</a>'
    - we use `href=""` attribute to provide destination we want link to go to.
    - Type:
        - Absolute Link Path: `protocol://domain/path`
        - Relative Link Path: `./dirpath/filename`
2. Images:
    - We add images using empty tag `<img>`
    - we use `src=""` attribute to provide address of image
    - we use `alt=""` to provide description of image.
        - `alt` attribute will be used in place of image if it can not loaded.

**Note:** In relative path to go to parent directory we use `../` . 