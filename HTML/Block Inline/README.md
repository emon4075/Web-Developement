# HTML Block & Inline Elements

## Overview
HTML elements are categorized as either block-level or inline elements based on how they display and interact with other elements. Understanding this distinction is crucial for proper HTML structure and CSS styling.

## Code Explanation

### Block-level Elements
```html
<div class="block-example">Division 1</div>
<div class="block-example">Division 2</div>

<p class="block-example">Paragraph1</p>
<p class="block-example">Paragraph2</p>

<h3 class="block-example">This is a heading (block)</h3>
```

**Characteristics of Block Elements:**
- Start on a new line
- Take up the full width available
- Can contain other block and inline elements
- Examples: `<div>`, `<p>`, `<h1>-<h6>`, `<ul>`, `<ol>`, `<li>`, `<table>`, `<form>`

### Inline Elements
```html
<p>This paragraph contains 
    <span class="inline-example">Hello</span>
    <span class="inline-example">World</span>
    inline elements.
</p>

<p>Here are more inline elements: 
    <a href="#" class="inline-example">Link</a>,
    <strong class="inline-example">Strong text</strong>,
    <em class="inline-example">Emphasized text</em>
</p>
```

**Characteristics of Inline Elements:**
- Do not start on a new line
- Only take up as much width as necessary
- Cannot contain block-level elements
- Examples: `<span>`, `<a>`, `<strong>`, `<em>`, `<img>`, `<input>`, `<label>`

### Mixed Block and Inline
```html
<div class="block-example">
    <h4>Block container with inline elements:</h4>
    <p>This is a <strong>paragraph</strong> (block) containing 
    <span style="color: blue;">inline spans</span> and 
    <a href="#">inline links</a>.</p>
</div>
```
- Block elements can contain inline elements
- Inline elements should not contain block elements
- Proper nesting is important for valid HTML

### Element Flow Demonstration
```html
<div style="background: red; color: white; padding: 5px;">Block Div 1</div>
<div style="background: blue; color: white; padding: 5px;">Block Div 2</div>

<p>Inline elements: 
    <span style="background: red; color: white; padding: 5px;">Span 1</span>
    <span style="background: blue; color: white; padding: 5px;">Span 2</span>
    <span style="background: green; color: white; padding: 5px;">Span 3</span>
</p>
```
- Block elements stack vertically
- Inline elements flow horizontally within their container

## Common Block Elements
- `<div>` - Generic container
- `<p>` - Paragraph
- `<h1>` to `<h6>` - Headings
- `<ul>`, `<ol>`, `<li>` - Lists
- `<table>`, `<tr>`, `<td>` - Tables
- `<form>` - Forms
- `<header>`, `<main>`, `<section>`, `<footer>` - Semantic containers

## Common Inline Elements
- `<span>` - Generic inline container
- `<a>` - Links
- `<strong>`, `<b>` - Bold text
- `<em>`, `<i>` - Italic text
- `<img>` - Images
- `<input>`, `<label>` - Form elements
- `<code>`, `<kbd>` - Code text

## CSS Display Property
You can change element behavior using CSS:
```css
/* Make inline element behave like block */
span {
    display: block;
}

/* Make block element behave like inline */
div {
    display: inline;
}

/* Inline-block: inline flow with block properties */
span {
    display: inline-block;
}
```

## Key Points
- Block elements create structure and layout
- Inline elements format content within blocks
- Proper nesting: blocks can contain inlines, but not vice versa
- CSS can override default display behavior
- Understanding this concept is essential for CSS layout

## Related Links
- [Block and Inline Elements - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements)
- [Inline Elements - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Inline_elements)
- [CSS Display Property - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/display)
- [HTML Block & Inline - W3Schools](https://www.w3schools.com/html/html_blocks.asp)