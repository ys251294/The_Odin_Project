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
    - `<html lang="en">`
    - `lang` specifies language if text entered int that element.
    - `lang` attribute is primarily used for improving the accessibility of the webpage.
3. Head Element
    - Put important meta information about our webpage and stuff required for webpages to render correctly in browser.
    - Should **not** use any element that display content onn the webpage.