# HTML Links

## Overview
HTML links allow users to navigate between pages, sections, and external resources. The `<a>` (anchor) element creates hyperlinks.

## Code Explanation

### Absolute URLs
```html
<a href="https://www.w3schools.com">Hello</a>
<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>
```
- Complete URLs including protocol (http/https)
- `target="_blank"` opens link in new tab

### Relative URLs
```html
<a href="hea.html">Hello</a>
```
- Links to files in the same directory or website

### Image Links
```html
<a href="hea.html"><img src="semantic-tags.png" alt="Image" style="width: 400; height: 300;"></a>
```
- Images can be wrapped in anchor tags to make them clickable

### Email Links
```html
<a href="mailto:someone@example.com">Send email</a>
```
- `mailto:` protocol opens default email client

### Links with Titles
```html
<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>
```
- `title` attribute provides tooltip text

### Bookmark Links
```html
<a href="#c1">Top</a>
<a href="\HTML\hea.html#c2">Here</a>
```
- `#` followed by ID creates internal page links
- Can link to sections within same page or other pages

## Key Points
- `href` attribute specifies the destination
- Links are inline elements by default
- Use descriptive link text for accessibility
- External links should often open in new tabs

## Related Links
- [HTML Links - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)
- [HTML Links - W3Schools](https://www.w3schools.com/html/html_links.asp)
- [Link Accessibility](https://webaim.org/techniques/hypertext/link_text)