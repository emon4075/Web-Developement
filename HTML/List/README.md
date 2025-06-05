# HTML Lists

## Overview
HTML provides three types of lists: unordered lists (bullet points), ordered lists (numbered), and description lists (terms and definitions).

## Code Explanation

### Unordered Lists
```html
<ul style="list-style-type: circle;">
    <li>Emon</li>
    <li>Emon</li>
    <li>Emon</li>
    <li>Emon</li>
</ul>
```
- `<ul>` - Unordered list container
- `<li>` - List item
- `list-style-type` - Changes bullet style (disc, circle, square, none)

### Ordered Lists
```html
<ol type="I">
    <li>Emon</li>
    <li>Emon</li>
    <li>Emon</li>
    <li>Emon</li>
</ol>
```
- `<ol>` - Ordered list container
- `type` attribute options: 1 (numbers), A (uppercase letters), a (lowercase letters), I (uppercase Roman), i (lowercase Roman)

### Ordered Lists with Custom Start
```html
<ol start="28">
    <li>Emon</li>
    <li>Emon</li>
    <li>Emon</li>
    <li>Emon</li>
</ol>
```
- `start` attribute sets the starting number

### Description Lists
```html
<dl>
    <dt>Coffee</dt>
    <dd>I Do Like</dd>
</dl>
```
- `<dl>` - Description list container
- `<dt>` - Description term
- `<dd>` - Description definition

## Key Points
- Lists are block-level elements
- List items can contain other HTML elements
- Lists can be nested inside each other
- Use appropriate list type for content structure

## Related Links
- [HTML Lists - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
- [HTML Lists - W3Schools](https://www.w3schools.com/html/html_lists.asp)
- [List Styling](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Styling_lists)