# HTML CSS

## Overview
CSS (Cascading Style Sheets) is used to style HTML elements. There are three ways to add CSS to HTML: inline, internal, and external stylesheets.

## Code Explanation

### Internal CSS (Style Tag)
```html
<style>
    .One {
        color: green;
        font-weight: bold;
        background-color: aliceblue;
    }

    #two {
        color: white;
        background-color: black;
    }
</style>
```
- CSS rules defined in `<style>` tag within `<head>`
- `.classname` - Selects elements with specific class
- `#idname` - Selects element with specific ID

### Inline CSS
```html
<h1 style="font-size: 60px; font-weight: lighter;">Hello World</h1>
<p style="font-family: courier; font-size: 200%;">This is a paragraph.</p>
```
- CSS properties applied directly to elements using `style` attribute
- Highest specificity but not reusable
- Use sparingly for unique styling

### CSS Classes
```html
<p class="One">Emon</p>
<p class="One">Saad</p>
<p class="One">Emran</p>
```
- Multiple elements can share the same class
- Defined with `.classname` in CSS
- Reusable styling for similar elements

### CSS IDs
```html
<p id="two">Anik</p>
```
- Unique identifier for single element
- Defined with `#idname` in CSS
- Should be unique per page

### Complex Styling
```html
<div style="background-color: #6a5acd; padding: 10px; font-family: Verdana;">
    <p>Hello World</p>
    <ul>
        <li>Emon</li>
        <li>Emon</li>
    </ul>
</div>
```
- Multiple CSS properties can be applied
- Properties separated by semicolons
- Nested elements inherit some properties

## CSS Properties Used
- `color` - Text color
- `background-color` - Background color
- `font-weight` - Text weight (bold, normal, etc.)
- `font-size` - Text size
- `font-family` - Font type
- `text-align` - Text alignment
- `padding` - Internal spacing
- `border` - Element border
- `float` - Element positioning

## Key Points
- External stylesheets are preferred for maintainability
- CSS follows specificity rules (inline > ID > class > element)
- Use classes for reusable styles, IDs for unique elements
- Keep content (HTML) and presentation (CSS) separated

## Related Links
- [CSS Introduction - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [HTML CSS - W3Schools](https://www.w3schools.com/html/html_css.asp)
- [CSS Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)
- [CSS Specificity](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity)