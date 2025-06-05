# HTML Page Title

## Overview
The HTML page title, defined by the `<title>` element, is one of the most important elements for SEO, user experience, and accessibility. It appears in browser tabs, search results, and social media shares.

## Code Explanation

### Basic Title Element
```html
<head>
    <title>HTML Page Title Examples - Learn HTML Titles</title>
</head>
```
- Must be placed inside the `<head>` section
- Only one `<title>` element per document
- Contains plain text only (no HTML tags)
- Required for valid HTML documents

### Title with Related Meta Tags
```html
<title>HTML Page Title Examples - Learn HTML Titles</title>
<meta name="description" content="Learn how to create effective HTML page titles...">
<meta name="keywords" content="HTML, page title, SEO, web development">
```
- Title works with meta description for search results
- Keywords meta tag is less important but can provide context
- Description should complement the title

### Social Media Integration
```html
<!-- Open Graph (Facebook, LinkedIn) -->
<meta property="og:title" content="HTML Page Title Examples - Complete Guide">
<meta property="og:description" content="Master HTML page titles with practical examples...">

<!-- Twitter Cards -->
<meta name="twitter:title" content="HTML Page Title Examples">
<meta name="twitter:description" content="Learn HTML page titles with examples...">
```
- Social platforms may use these instead of the main title
- Allows customization for different sharing contexts
- Important for social media marketing

### Dynamic Title Changes
```javascript
// Change title with JavaScript
document.title = "New Page Title";

// Get current title
console.log(document.title);

// Example: Update title based on user action
function changeTitle() {
    document.title = "Title Changed! - Dynamic HTML Title";
}
```
- Titles can be changed dynamically with JavaScript
- Useful for single-page applications
- Updates browser tab in real-time

## Title Best Practices

### Length Guidelines
- **Optimal length**: 50-60 characters
- **Google display limit**: ~70 characters
- **Mobile displays**: Often shorter limits
- **Consideration**: Longer titles get truncated with "..."

### Structure Patterns

#### Pattern 1: Keyword | Brand
```html
<title>Running Shoes | SportStore</title>
```

#### Pattern 2: Page Name - Site Name
```html
<title>Contact Us - TechCorp Solutions</title>
```

#### Pattern 3: Primary: Secondary | Brand
```html
<title>Web Development: Beginner's Guide | CodeAcademy</title>
```

### Good Title Examples

#### E-commerce Product
```html
<title>iPhone 15 Pro - 128GB Space Black | Apple Store</title>
```
**Why it works:**
- Specific product name
- Key specifications
- Clear brand identification
- Under character limit

#### Blog Article
```html
<title>10 Best CSS Grid Techniques for 2025 | Web Dev Blog</title>
```
**Why it works:**
- Descriptive and specific
- Includes current year
- Numbers attract attention
- Clear site identification

#### Local Business
```html
<title>Mario's Pizza - Best Italian Restaurant in New York | Order Online</title>
```
**Why it works:**
- Business name upfront
- Location specified
- Value proposition
- Call-to-action included

### Poor Title Examples

#### Too Generic
```html
<title>Home Page</title>
```
**Problems:**
- Doesn't describe content
- No brand identification
- Provides no value to users

#### Too Long
```html
<title>Welcome to our amazing website where you can find everything you need for your home, garden, pets, electronics...</title>
```
**Problems:**
- Exceeds character limits
- Gets truncated in results
- Keyword stuffing appearance

#### Keyword Stuffing
```html
<title>Pizza, Best Pizza, NYC Pizza, Italian Pizza, Cheap Pizza</title>
```
**Problems:**
- Poor readability
- Spammy appearance
- May trigger search engine penalties

## Page Type Specific Titles

### Homepage
```html
<title>CompanyName - Brief Description of What You Do</title>
```

### Category Pages
```html
<title>Men's Clothing - Fashion & Style | StoreName</title>
```

### Product Pages
```html
<title>Product Name - Key Feature | Store Name</title>
```

### Blog Posts
```html
<title>How to Learn HTML in 2025 | Blog Name</title>
```

### Contact Pages
```html
<title>Contact Us - Get in Touch | Company Name</title>
```

### Error Pages
```html
<title>404 - Page Not Found | Site Name</title>
```

## SEO Impact

### Search Engine Results
- Primary clickable element in search results
- Affects click-through rates significantly
- Should match search intent
- Include primary keywords naturally

### Ranking Factors
- Direct ranking signal for search engines
- Should be unique across all pages
- Relevance to page content is crucial
- Avoid duplicate titles across site

### User Experience
- Helps users understand page content
- Important for browser bookmarks
- Displayed in browser history
- Shows in shared links

## Technical Considerations

### Character Encoding
```html
<meta charset="UTF-8">
<title>Special Characters: Café, Résumé, naïve</title>
```
- Ensure proper character encoding
- UTF-8 supports international characters
- Test special characters display correctly

### Accessibility
- Screen readers announce page titles
- Important for navigation context
- Should be descriptive and meaningful
- Helps users understand page purpose

### Performance
- Titles don't affect page load speed
- Keep concise for better usability
- Avoid unnecessary complexity

## Testing and Optimization

### Tools for Testing
1. **Google Search Console** - See how titles appear in search
2. **SEO Browser Extensions** - Preview SERP appearance
3. **Social Media Debuggers** - Test social sharing appearance
4. **Analytics** - Monitor click-through rates

### A/B Testing Titles
- Test different title variations
- Monitor click-through rates
- Consider seasonal relevance
- Update based on performance data

### Common Mistakes to Avoid
1. **Duplicate titles** across multiple pages
2. **Missing titles** (leaves pages untitled)
3. **Misleading titles** that don't match content
4. **Overly complex** titles that confuse users
5. **Ignoring mobile** display limitations

## Key Points
- Title is crucial for SEO and user experience
- Appears in multiple contexts (tabs, search, social)
- Should be unique, descriptive, and concise
- Include relevant keywords naturally
- Test and optimize based on performance
- Consider different contexts (search, social, bookmarks)

## Related Links
- [HTML Title Element - MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title)
- [Title Tag SEO Best Practices - Moz](https://moz.com/learn/seo/title-tag)
- [HTML Head Elements - W3Schools](https://www.w3schools.com/html/html_head.asp)
- [Open Graph Protocol](https://ogp.me/)
- [Twitter Card Documentation](https://developer.twitter.com/en/docs/twitter-for-websites/cards/overview/abouts-cards)