# HTML Colors

## Overview
HTML supports various ways to specify colors for text, backgrounds, borders, and other elements. Colors can be defined using names, RGB values, or hexadecimal codes.

## Code Explanation

### Named Colors
```html
<body style="background-color: lightblue;">
<h1 style="background-color: dodgerblue; text-align: center">Hello World</h1>
<p style="color: tomato; border: 2px dashed black;">Hello World</p>
```
- HTML supports 140 named colors
- Examples: red, blue, green, lightblue, dodgerblue, tomato
- Easy to remember but limited options

### RGB and RGBA Colors
```html
<h2 style="background-color: rgba(90, 99, 32, 0.3);">Heading</h2>
```
- RGB: `rgb(red, green, blue)` - values from 0-255
- RGBA: `rgba(red, green, blue, alpha)` - alpha for transparency (0-1)
- More precise color control
- Alpha channel allows transparency effects

### Hexadecimal Colors
```html
<h3 style="background-color: #6a5acd;">Hello World</h3>
```
- Format: `#RRGGBB` or `#RGB`
- Each pair represents red, green, blue values in hexadecimal (00-FF)
- Most common format in web development
- Compact and widely supported

### CSS Color Classes
```css
.colorExample {
    background-color: burlywood;
    color: darkblue;
    padding: 10px;
}
```
- Define colors in CSS classes for reusability
- Better separation of content and styling
- Easier to maintain and update

## Color Properties
- `color` - Text color
- `background-color` - Background color
- `border-color` - Border color

## Key Points
- Use consistent color schemes for better design
- Ensure sufficient contrast for accessibility
- Test colors for color-blind users
- Consider using CSS variables for color themes

## Related Links
- [HTML Colors - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value)
- [HTML Colors - W3Schools](https://www.w3schools.com/html/html_colors.asp)
- [Color Accessibility](https://webaim.org/articles/contrast/)
- [Color Picker Tool](https://htmlcolorcodes.com/)