# HTML Comments

## Overview
HTML comments allow developers to add notes, explanations, or temporarily hide content within HTML documents. Comments are not displayed in the browser but are visible in the source code.

## Code Explanation

### Basic Comment Syntax
```html
<!-- This is a single-line HTML comment -->
```
- Comments start with `<!--` and end with `-->`
- Content between these markers is ignored by the browser
- Comments can appear anywhere in HTML documents

### Multi-line Comments
```html
<!-- 
    This is a multi-line HTML comment
    It can span multiple lines
    and is useful for longer explanations
-->
```
- Same syntax as single-line comments
- Can span multiple lines for detailed documentation
- Useful for explaining complex code sections

### Commenting Out Code
```html
<!-- <p>This paragraph is commented out and won't display</p> -->

<!--
<div>
    <h3>Hidden Section</h3>
    <p>This entire section is commented out.</p>
    <ul>
        <li>Hidden list item 1</li>
        <li>Hidden list item 2</li>
    </ul>
</div>
-->
```
- Temporarily hide HTML elements without deleting them
- Useful for testing and debugging
- Can comment out single elements or entire sections

### Inline Comments
```html
<p>This paragraph has a <!-- inline comment --> within it.</p>
```
- Comments can be placed within HTML content
- The commented text doesn't affect the visible content
- Useful for marking specific parts of content

### Developer Notes
```html
<!-- TODO: Add more content here -->
<!-- FIXME: Fix the styling of this section -->
<!-- NOTE: This section needs review -->
```
Common developer comment patterns:
- `TODO:` - Tasks to be completed
- `FIXME:` - Code that needs fixing
- `NOTE:` - Important information
- `HACK:` - Temporary workaround
- `WARNING:` - Potential issues

### Code Documentation
```html
<!-- Date: 2025-06-05 -->
<!-- Author: emon4075 -->
<!-- Version: 1.0 -->

<!-- Begin navigation section -->
<nav>
    <!-- Navigation content -->
</nav>
<!-- End navigation section -->
```
- Document code authorship and dates
- Mark beginning and end of sections
- Provide context for future maintenance

### Conditional Comments (Deprecated)
```html
<!--[if IE]>
    <p>This content only shows in Internet Explorer</p>
<![endif]-->
```
- Legacy feature for Internet Explorer
- No longer supported in modern browsers
- Included for historical reference only

### Performance and Debug Notes
```html
<!-- 
    Performance Note: 
    Large images below may affect page load time
    Consider optimizing or lazy loading
-->

<!-- Debug information (remove in production) -->
<!-- User ID: 12345 -->
<!-- Session: active -->
```
- Document performance considerations
- Include debug information for development
- Remember to remove sensitive debug info in production

### Section Markers
```html
<!-- ========== HEADER SECTION ========== -->
<header>
    <!-- Header content -->
</header>

<!-- ========== MAIN CONTENT ========== -->
<main>
    <!-- Main content -->
</main>
```
- Use visual markers to separate major sections
- Makes code easier to navigate
- Consistent formatting improves readability

## Comment Best Practices

### Do Use Comments For:
1. **Explaining complex logic**: Why something is done a certain way
2. **Temporary code removal**: Testing different approaches
3. **Section markers**: Organizing large HTML files
4. **Developer notes**: TODOs, FIXMEs, warnings
5. **Documentation**: Author, date, version information
6. **API documentation**: Explaining data structures or requirements

### Don't Use Comments For:
1. **Obvious code**: Don't comment what the code clearly does
2. **Sensitive information**: Passwords, keys, personal data
3. **Large amounts of dead code**: Delete instead of commenting
4. **Version control**: Git handles this better than comments
5. **Debugging in production**: Remove debug comments before deployment

### Comment Formatting Tips:
```html
<!-- Single line comment -->

<!-- 
Multi-line comment
with proper indentation
and clear formatting
-->

<!-- ==================== -->
<!-- MAJOR SECTION HEADER -->
<!-- ==================== -->
```

## Security Considerations
- Comments are visible in page source
- Never include sensitive information in comments
- Remove debug information before production deployment
- Be aware that comments add to page size

## Key Points
- Comments don't affect page display but are visible in source
- Use `<!-- comment text -->` syntax
- Can span single or multiple lines
- Useful for documentation, debugging, and temporary code removal
- Clean up comments before production deployment

## Related Links
- [HTML Comments - MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started#html_comments)
- [HTML Comments - W3Schools](https://www.w3schools.com/html/html_comments.asp)
- [Code Documentation Best Practices](https://stackoverflow.blog/2021/12/23/best-practices-for-writing-code-comments/)
- [Clean Code Comments](https://blog.codinghorror.com/code-tells-you-how-comments-tell-you-why/)