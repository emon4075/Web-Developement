# CSS Box Model

## Overview
The CSS Box Model is a fundamental concept that describes how elements are structured and spaced on a webpage. Every HTML element is essentially a rectangular box.

## Box Model Components
The box model consists of four main areas (from inside to outside):

1. **Content** - The actual content of the element (text, images, etc.)
2. **Padding** - Space between content and border (inside the element)
3. **Border** - The boundary around the padding and content
4. **Margin** - Space outside the border (between elements)

## Box Model Properties
```css
.element {
    /* Content area */
    width: 200px;
    height: 100px;
    
    /* Padding */
    padding: 10px;
    
    /* Border */
    border: 2px solid black;
    
    /* Margin */
    margin: 15px;
}