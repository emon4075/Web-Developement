# HTML Classes

## Overview
HTML classes are used to apply CSS styles to multiple elements. Classes provide a way to group elements and apply consistent styling across your website.

## Code Explanation

### Defining CSS Classes
```css
.One {
    color: green;
    font-weight: bold;
    background-color: aliceblue;
}

.highlight {
    background-color: yellow;
    padding: 5px;
}
```
- Class selectors start with a dot (`.`)
- Class names should be descriptive and meaningful
- Multiple properties can be defined for each class

### Applying Single Classes
```html
<p class="One">Emon</p>
<p class="One">Saad</p>
<p class="One">Emran</p>
```
- Use `class` attribute to apply styles
- Multiple elements can share the same class
- Promotes consistency and reusability

### Applying Multiple Classes
```html
<p class="One highlight">Multiple Classes Example</p>
<h2 class="center large-text">Centered Large Text</h2>
```
- Multiple classes separated by spaces
- All class styles are applied to the element
- Later classes can override earlier ones if conflicts exist

### Combining Classes with Inline Styles
```html
<div class="One" style="border: 2px solid red;">
    <p>Class with additional inline styling</p>
</div>
```
- Inline styles have higher specificity than classes
- Use sparingly for unique modifications
- Classes provide base styling, inline adds specific changes

## Class Naming Conventions
- Use descriptive names: `.navigation`, `.highlight`, `.error-message`
- Use kebab-case: `.large-text`, `.primary-button`
- Avoid styling-specific names: prefer `.warning` over `.red-text`
- Be consistent throughout your project

## Key Points
- Classes are reusable across multiple elements
- Elements can have multiple classes
- Classes have lower specificity than IDs but higher than element selectors
- Use classes for styling, IDs for unique identification

## Related Links
- [CSS Classes - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors)
- [HTML Classes - W3Schools](https://www.w3schools.com/html/html_classes.asp)
- [CSS Naming Conventions](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Organizing)