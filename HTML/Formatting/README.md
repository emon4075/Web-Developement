# HTML Formatting

## Overview
HTML provides various elements to format text and give it semantic meaning. These elements help structure content and improve accessibility.

## Code Explanation

### Bold and Strong Text
```html
<b>Bold Text</b>
<strong>Strong Text</strong>
```
- `<b>` - Makes text bold (visual formatting only)
- `<strong>` - Indicates strong importance (semantic + bold styling)
- Use `<strong>` for important content, `<b>` for stylistic bold

### Italic and Emphasis
```html
<i>Italic Text</i>
<em>Emphasized Text</em>
```
- `<i>` - Makes text italic (visual formatting only)
- `<em>` - Indicates emphasis (semantic + italic styling)
- Use `<em>` for emphasized content, `<i>` for stylistic italic

### Deleted and Inserted Text
```html
<strike>Striked Text</strike>
<p>My Favorite Color is <del>Red</del> Blue</p>
<p>My Favorite Color is <del>Red</del> <ins>Blue</ins></p>
```
- `<strike>` - Deprecated, use `<del>` instead
- `<del>` - Represents deleted/removed text
- `<ins>` - Represents inserted/added text

### Small and Highlighted Text
```html
<small>Small Text</small>
<mark>Marked Text Text</mark>
```
- `<small>` - Represents side comments or fine print
- `<mark>` - Highlights text (like a highlighter pen)

### Superscript and Subscript
```html
<p>This is <sup>Superscript</sup></p>
<p>This is <sub>Subscript</sub></p>
```
- `<sup>` - Superscript text (raised above baseline)
- `<sub>` - Subscript text (lowered below baseline)
- Useful for mathematical formulas, footnotes, chemical formulas

## Key Points
- Choose semantic elements over purely visual ones
- Semantic elements improve accessibility and SEO
- Screen readers understand the meaning of semantic tags
- CSS can be used to style these elements differently

## Related Links
- [HTML Text Formatting - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element#inline_text_semantics)
- [HTML Formatting - W3Schools](https://www.w3schools.com/html/html_formatting.asp)
- [Semantic HTML](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantic_elements)