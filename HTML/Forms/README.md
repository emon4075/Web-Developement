# HTML Forms

## Overview
HTML forms allow users to input data that can be sent to a server for processing. Forms are essential for user interaction on websites.

## Code Explanation

### Form Structure
```html
<form action="">
    <!-- Form elements go here -->
</form>
```
- `<form>` - Container for all form elements
- `action` - URL where form data is sent (empty means current page)

### Text Input Fields
```html
<label for="fname">First Name:</label>
<input type="text" name="fname" id="fname">
```
- `<label>` - Describes the input field
- `for` attribute matches the input's `id`
- `<input type="text">` - Single-line text input
- `name` - Used to identify data when submitted
- `id` - Unique identifier for the element

### Radio Buttons
```html
<input type="radio" name="language" id="html" value="html">
<label for="html">HTML</label>
```
- `type="radio"` - Creates radio button
- Same `name` groups radio buttons together
- Only one radio button per group can be selected
- `value` - Data sent when form is submitted

### Checkboxes
```html
<input type="checkbox" name="css_check" id="css_check">
<label for="css_check">CSS</label>
```
- `type="checkbox"` - Creates checkbox
- Multiple checkboxes can be selected
- Independent of other form elements

### Submit Button
```html
<input type="submit" value="Submit" id="Submit">
```
- `type="submit"` - Creates form submission button
- `value` - Text displayed on button
- Triggers form submission when clicked

## Key Points
- Always associate labels with form controls
- Use appropriate input types for data validation
- Group related radio buttons with same `name`
- Form data is sent as name-value pairs

## Related Links
- [HTML Forms - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)
- [HTML Forms - W3Schools](https://www.w3schools.com/html/html_forms.asp)
- [Form Validation](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation)