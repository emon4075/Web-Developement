# HTML Quotations

## Overview
HTML provides several elements for marking up quotations, citations, abbreviations, and contact information. These semantic elements help structure content meaningfully and improve accessibility.

## Code Explanation

### Blockquote Element
```html
<blockquote cite="https://www.google.com">
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti rerum nihil,
    quia enim possimus earum! Sit, ullam. Expedita, rerum consequatur?
</blockquote>
```
- `<blockquote>` - For longer quotations (block-level)
- `cite` attribute - URL of the source (optional)
- Typically indented by browsers by default
- Can contain multiple paragraphs and other block elements

### Structured Blockquote
```html
<blockquote cite="https://www.brainyquote.com/quotes/albert_einstein_100015">
    <p>Imagination is more important than knowledge...</p>
    <footer>— <cite>Albert Einstein</cite></footer>
</blockquote>
```
- Use `<p>` for quote content
- Use `<footer>` for attribution
- Use `<cite>` for the source/author name

### Inline Quotations
```html
<p>Lorem ipsum dolor sit amet <q>consectetur adipisicing elit</q> dicta, quas!</p>
<p>As Shakespeare wrote, <q>To be or not to be, that is the question.</q></p>
```
- `<q>` - For short, inline quotations
- Browsers automatically add quotation marks
- Can include `cite` attribute for source URL

### Abbreviations
```html
<p><abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
<p>The <abbr title="HyperText Markup Language">HTML</abbr> specification...</p>
```
- `<abbr>` - Marks up abbreviations and acronyms
- `title` attribute provides full expansion
- Creates dotted underline in most browsers
- Screen readers can announce the full form

### Address Element
```html
<address>
    Name: Emon <br>
    University: University of Chittagong <br>
    Department: CSE <br>
    Email: <a href="mailto:emon@example.com">emon@example.com</a><br>
    Phone: <a href="tel:+1234567890">+123-456-7890</a>
</address>
```
- `<address>` - Contact information for document/article
- Usually styled in italics by default
- Can contain links for email and phone
- Should be used for contact info, not postal addresses in content

### Cite Element
```html
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
<p>According to <cite>MDN Web Docs</cite>, the cite element...</p>
```
- `<cite>` - References to creative works, publications, sources
- For titles of books, articles, movies, songs, etc.
- Usually styled in italics
- Should not be used for people's names (use regular text)

### Complex Quotations
```html
<blockquote cite="https://example.com/source">
    <p>This is the first paragraph of a longer quotation...</p>
    <p>This is the second paragraph of the same quotation...</p>
</blockquote>
<p>Source: <cite>Example Publication</cite>, 2025</p>
```
- Blockquotes can contain multiple paragraphs
- Attribution can be placed outside the blockquote
- Maintain proper semantic structure

### Nested Quotations
```html
<p>John said, <q>Mary told me, <q>I'll be there at 5 PM</q>, so we should wait for her.</q></p>
```
- Quotations can be nested inside each other
- Browsers handle nested quotation marks automatically
- Useful for reported speech scenarios

### International Quotations
```html
<p lang="es">Como dice el refrán español: <q>No hay mal que por bien no venga.</q></p>
<blockquote lang="la" cite="https://example.com/latin">
    <p>Carpe diem, quam minimum credula postero.</p>
    <footer>— <cite>Horace</cite></footer>
</blockquote>
```
- Use `lang` attribute for quotes in different languages
- Helps with proper pronunciation by screen readers
- Browsers may apply language-specific quotation marks

## Semantic Meaning and Accessibility

### Screen Reader Benefits
- `<abbr>` announcements help users understand acronyms
- `<cite>` provides context about sources
- `<address>` clearly identifies contact information
- `<q>` and `<blockquote>` indicate quoted content

### SEO Benefits
- Search engines understand content structure better
- Citations may help with content credibility
- Proper markup improves content indexing

## Styling Quotations

### CSS for Blockquotes
```css
blockquote {
    border-left: 4px solid #ccc;
    margin: 20px 0;
    padding-left: 20px;
    font-style: italic;
    background-color: #f9f9f9;
}
```

### CSS for Citations
```css
cite {
    font-style: italic;
    color: #666;
}
```

## Best Practices
1. **Use appropriate elements**: `<q>` for inline, `<blockquote>` for block quotes
2. **Provide sources**: Use `cite` attribute when possible
3. **Structure properly**: Use `<p>`, `<footer>`, `<cite>` within blockquotes
4. **Don't overuse**: Only for actual quotations, not emphasis
5. **Consider accessibility**: Ensure proper context for screen readers
6. **Validate markup**: Check that nested elements are properly closed

## Key Points
- Different elements serve different quotation purposes
- Semantic markup improves accessibility and SEO
- Browsers provide default styling that can be customized
- Citations and sources add credibility to content
- Proper nesting is crucial for valid HTML

## Related Links
- [HTML Quotation Elements - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote)
- [HTML Text Fundamentals - MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
- [HTML Quotations - W3Schools](https://www.w3schools.com/html/html_quotation_elements.asp)
- [Semantic HTML Guide](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantic_elements)