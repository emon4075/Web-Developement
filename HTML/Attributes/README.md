# HTML Attributes

## Overview
HTML attributes provide additional information about HTML elements. They are always specified in the opening tag and usually come in name/value pairs like `name="value"`.

## Code Explanation

### Global Attributes
```html
<h1 id="main-title" class="heading" title="Main page heading">HTML Attributes</h1>
```
Global attributes can be used on any HTML element:
- `id` - Unique identifier for the element
- `class` - CSS class name(s) for styling
- `title` - Tooltip text displayed on hover
- `style` - Inline CSS styling
- `lang` - Language of the element's content
- `dir` - Text direction (ltr, rtl)

### Image Attributes
```html
<img src="semantic-tags.png" 
     width="200" 
     height="200" 
     alt="Semantic HTML Tags Diagram"
     title="HTML5 Semantic Elements">
```
- `src` - Image source URL (required)
- `alt` - Alternative text for accessibility (required)
- `width` and `height` - Image dimensions
- `title` - Tooltip text

### Link Attributes
```html
<a href="https://www.w3schools.com" 
   target="_blank" 
   title="Go to W3Schools HTML section"
   rel="noopener">Visit W3Schools</a>
```
- `href` - Destination URL (required)
- `target` - Where to open the link (_blank, _self, _parent, _top)
- `rel` - Relationship between current and linked document
- `title` - Additional information about the link

### Form Attributes
```html
<input type="text" 
       id="username" 
       name="username" 
       placeholder="Enter your username"
       required
       maxlength="20"
       autocomplete="username">
```
- `type` - Input type (text, email, password, etc.)
- `name` - Form field name for server processing
- `placeholder` - Hint text displayed in empty field
- `required` - Makes field mandatory
- `maxlength` - Maximum number of characters
- `autocomplete` - Browser autocomplete behavior

### Table Attributes
```html
<th colspan="2">Student Information</th>
<td rowspan="2">Details</td>
```
- `colspan` - Number of columns a cell spans
- `rowspan` - Number of rows a cell spans
- `border` - Table border width
- `cellpadding` - Space inside cells
- `cellspacing` - Space between cells

### Custom Data Attributes
```html
<div data-user-id="12345" 
     data-role="admin" 
     data-created-date="2025-06-05">
    User Information Container
</div>
```
- Start with `data-` prefix
- Store custom data for JavaScript access
- Use kebab-case for attribute names
- Accessible via `dataset` property in JavaScript

### Boolean Attributes
```html
<input type="checkbox" checked disabled>
<input type="text" readonly value="Read-only text">
<script defer src="script.js"></script>
```
Boolean attributes don't need values:
- `checked` - Checkbox/radio button selected
- `disabled` - Form element disabled
- `readonly` - Input field read-only
- `required` - Form field required
- `hidden` - Element hidden
- `defer` - Script execution deferred

### Accessibility Attributes
```html
<button aria-label="Close dialog" 
        aria-describedby="close-help"
        role="button">×</button>
<div id="close-help" hidden>Click to close the dialog</div>
```
ARIA attributes improve accessibility:
- `aria-label` - Accessible name for element
- `aria-describedby` - References descriptive text
- `role` - Element's purpose or function
- `tabindex` - Tab order for keyboard navigation

### Language and Direction
```html
<p lang="es" dir="ltr">Hola, ¿cómo estás?</p>
<p lang="ar" dir="rtl">مرحبا، كيف حالك؟</p>
```
- `lang` - Language code (es, en, ar, etc.)
- `dir` - Text direction (ltr = left-to-right, rtl = right-to-left)

## Attribute Syntax Rules
1. **Case-insensitive**: `ID` and `id` are the same
2. **Quotes**: Use single or double quotes around values
3. **No spaces**: Around the equals sign
4. **Required quotes**: For values with spaces or special characters
5. **Boolean attributes**: Can be written as `checked` or `checked="checked"`

## Common Attribute Categories
- **Global**: Available on all elements (id, class, title, style, etc.)
- **Event**: Handle user interactions (onclick, onload, onchange, etc.)
- **Form**: Specific to form elements (name, value, placeholder, etc.)
- **Media**: For images, audio, video (src, alt, controls, etc.)
- **Link**: For anchor elements (href, target, rel, etc.)
- **Table**: For table elements (colspan, rowspan, etc.)
- **ARIA**: For accessibility (aria-label, role, etc.)

## Key Points
- Attributes modify element behavior and appearance
- Always use quotes around attribute values
- Some attributes are required for valid HTML
- Custom data attributes enable JavaScript data storage
- Accessibility attributes improve user experience
- Boolean attributes don't need explicit values

## Related Links
- [HTML Attributes - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)
- [Global Attributes - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)
- [HTML Attributes - W3Schools](https://www.w3schools.com/html/html_attributes.asp)
- [ARIA Attributes](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Attributes)
- [Data Attributes](https://developer.mozilla.org/en-US/docs/Learn/HTML/Howto/Use_data_attributes)