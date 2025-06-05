# HTML Id

## Overview
The HTML `id` attribute provides a unique identifier for HTML elements. IDs are used for CSS styling, JavaScript targeting, and creating bookmarks within pages.

## Code Explanation

### ID for CSS Styling
```html
<h1 id="c1">Hello World</h1>
<p id="two">Anik</p>
```

```css
#two {
    color: white;
    background-color: black;
}

#c1 {
    color: blue;
    border-bottom: 2px solid blue;
}
```
- ID selectors in CSS start with hash (`#`)
- Each ID should be unique within the page
- IDs have higher specificity than classes

### ID for Form Elements
```html
<label for="username">Username:</label>
<input type="text" id="username" name="username">
<input type="submit" value="Submit" id="Submit">
```
- `for` attribute in labels should match input `id`
- Creates accessibility connection between label and input
- Form elements often use IDs for JavaScript interaction

### ID for Page Navigation
```html
<h2 id="section1">Section 1</h2>
<h2 id="section2">Section 2</h2>

<a href="#c1">Go to Top</a>
<a href="#section1">Go to Section 1</a>
<a href="#section2">Go to Section 2</a>
```
- IDs create bookmark anchors within pages
- Links with `#idname` jump to that element
- Useful for navigation in long documents

## ID Rules and Best Practices
- **Uniqueness**: Each ID must be unique within the page
- **Naming**: Use descriptive names (e.g., `main-header`, `contact-form`)
- **Case-sensitive**: IDs are case-sensitive
- **No spaces**: Use hyphens or underscores instead of spaces
- **Start with letter**: IDs should start with a letter, not a number

## Common Use Cases
1. **CSS Styling**: Unique styling for specific elements
2. **JavaScript**: Targeting specific elements for interaction
3. **Form Labels**: Connecting labels with form controls
4. **Page Navigation**: Creating internal page links
5. **Fragment URLs**: Direct linking to page sections

## Key Points
- IDs have higher CSS specificity than classes
- Use IDs sparingly - prefer classes for reusable styles
- Essential for accessibility in forms
- Required for JavaScript DOM manipulation

## Related Links
- [HTML Id - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/id)
- [CSS ID Selectors - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/ID_selectors)
- [HTML Id - W3Schools](https://www.w3schools.com/html/html_id.asp)
- [Form Accessibility](https://webaim.org/techniques/forms/controls)