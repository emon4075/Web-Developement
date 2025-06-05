# HTML Paragraphs

## Overview
HTML paragraphs are used to group related sentences and create readable text blocks. The `<p>` element represents a paragraph of text.

## Code Explanation

### Basic Paragraph
```html
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
```
- Basic paragraph element containing text content

### Paragraph with Attributes
```html
<p title="'Title' Attribute">Lorem ipsum dolor sit amet...</p>
```
- `title` attribute provides tooltip text on hover

### Styled Paragraphs
```html
<p style="font-family:courier; font-size: 200%;">This is a paragraph.</p>
<p style="color: tomato; border: 2px dashed black;">Hello World</p>
```
- CSS styling can be applied inline or via classes

### Preformatted Text
```html
<pre style="background-color: rgb(44, 147, 39); color: whitesmoke;">
    Hello
    World
    I am
    King
</pre>
```
- `<pre>` preserves whitespace and formatting

### Inline Elements in Paragraphs
```html
<p>My <span style="color: red;">Mother</span> is a <span style="font-family: Verdana;">Teacher</span>.</p>
```
- `<span>` elements can style parts of paragraphs

## Key Points
- Paragraphs are block-level elements
- Browser adds margins around paragraphs by default
- Whitespace is collapsed in regular paragraphs
- Use `<pre>` to preserve formatting

## Related Links
- [HTML Paragraphs - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p)
- [HTML Paragraphs - W3Schools](https://www.w3schools.com/html/html_paragraphs.asp)
- [Preformatted Text - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/pre)