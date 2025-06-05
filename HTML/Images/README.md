# HTML Images

## Overview
The HTML `<img>` element embeds images into web pages. Images make content more engaging and visually appealing.

## Code Explanation

### Basic Image Syntax
```html
<img src="semantic-tags.png" width="200" height="200" alt="Hello">
```
- `src` - specifies the image source/path
- `width` and `height` - set image dimensions
- `alt` - alternative text for accessibility

### Styled Images
```html
<img src="semantic-tags.png" alt="Fooler" style="width: 200; height: 200;">
```
- CSS styling preferred over width/height attributes
- More flexible and maintainable

### Animated Images
```html
<img src="Monsters Inc Animation GIF by Disney Pixar.gif" alt="GIF" 
     style="width: 400px; height: 300px; float: right;">
```
- GIFs and other animated formats supported
- `float` property for text wrapping

### Images as Links
```html
<a href="hea.html"><img src="semantic-tags.png" alt="Image" style="width: 400; height: 300;"></a>
```
- Images can be wrapped in anchor tags to make them clickable

## Key Points
- Always include `alt` attribute for accessibility
- Use appropriate file formats (JPEG, PNG, GIF, WebP)
- Optimize images for web to reduce load times
- Consider responsive image techniques

## Image Formats
- **JPEG** - Best for photos
- **PNG** - Best for graphics with transparency
- **GIF** - Best for simple animations
- **WebP** - Modern format with better compression

## Related Links
- [HTML Images - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)
- [HTML Images - W3Schools](https://www.w3schools.com/html/html_images.asp)
- [Image Optimization](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)