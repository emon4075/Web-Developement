# HTML Iframes

## Overview
HTML iframes (inline frames) allow you to embed another HTML document within the current document. They create a rectangular region where you can display content from another source.

## Code Explanation

### Basic Iframe
```html
<iframe src="https://github.com/" frameborder="1" height="300" width="400" title="GitHub"></iframe>
```
- `src` - URL of the page to embed
- `frameborder` - Whether to show border (1 = yes, 0 = no)
- `height` and `width` - Iframe dimensions
- `title` - Accessibility description

### Iframe Attributes
```html
<iframe src="https://www.example.com" 
        frameborder="0" 
        height="250" 
        width="500" 
        title="Example">
</iframe>
```
- `frameborder="0"` removes the default border
- Dimensions can be set in pixels or percentages
- `title` attribute is important for screen readers

### Responsive Iframe
```html
<iframe class="responsive-iframe" 
        src="https://www.w3schools.com" 
        title="W3Schools">
</iframe>
```

```css
.responsive-iframe {
    width: 100%;
    height: 300px;
    border: 1px solid #ddd;
}
```
- Use CSS for better control over styling
- `width: 100%` makes iframe responsive
- CSS borders are more flexible than `frameborder`

### Iframe with Scrolling
```html
<iframe src="https://developer.mozilla.org" 
        width="600" 
        height="200" 
        frameborder="1" 
        scrolling="yes" 
        title="MDN Web Docs">
</iframe>
```
- `scrolling` attribute controls scroll bars
- Values: `yes`, `no`, `auto` (default)

### Fallback Content
```html
<iframe src="sample-page.html" 
        width="100%" 
        height="200" 
        frameborder="1" 
        title="Local Page">
    <p>Your browser does not support iframes.</p>
</iframe>
```
- Content between iframe tags shows if iframe fails to load
- Important for accessibility and older browsers

## Common Use Cases
1. **Embedding Videos**: YouTube, Vimeo players
2. **Maps**: Google Maps, other mapping services
3. **Social Media**: Twitter feeds, Facebook posts
4. **External Widgets**: Weather widgets, calendars
5. **Documentation**: Embedding help pages or tutorials
6. **Payment Forms**: Secure payment processors

## Security Considerations
- **Same-Origin Policy**: Restricts cross-origin access
- **X-Frame-Options**: Some sites prevent iframe embedding
- **Sandbox Attribute**: Restricts iframe capabilities
- **Content Security Policy**: May block iframe sources

### Sandbox Attribute
```html
<iframe src="untrusted-content.html" 
        sandbox="allow-scripts allow-forms"
        title="Sandboxed Content">
</iframe>
```
- `sandbox` restricts iframe capabilities
- Values: `allow-scripts`, `allow-forms`, `allow-same-origin`, etc.

## Best Practices
1. **Always include `title` attribute** for accessibility
2. **Use HTTPS sources** when possible for security
3. **Set appropriate dimensions** to avoid layout issues
4. **Consider responsive design** for mobile devices
5. **Test iframe content** across different browsers
6. **Provide fallback content** for unsupported browsers

## CSS Styling
```css
iframe {
    border: none;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

/* Responsive iframe container */
.iframe-wrapper {
    position: relative;
    padding-bottom: 56.25%; /* 16:9 aspect ratio */
    height: 0;
    overflow: hidden;
}

.iframe-wrapper iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}
```

## Key Points
- Iframes create isolated browsing contexts
- Cross-origin restrictions may apply
- Always consider security implications
- Test accessibility with screen readers
- Modern alternatives include embed and object elements

## Related Links
- [HTML Iframes - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe)
- [HTML Iframes - W3Schools](https://www.w3schools.com/html/html_iframe.asp)
- [Iframe Security](https://developer.mozilla.org/en-US/docs/Web/Security/Same-origin_policy)
- [Responsive Iframes](https://css-tricks.com/responsive-iframes/)