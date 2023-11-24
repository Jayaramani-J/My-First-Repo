# CSS Properties and Values Cheatsheet

## Introduction

This cheatsheet provides a quick reference for common CSS properties and values used in web development.

## Selectors

- **Element Selector:**
  ```css
  element
  {
    property: value;
  }

- **Class Selector:**
  ```css
  .classname
  {
    property: value;
  }

- **ID Selector:**
  ```css 
  #idname
  {
    property: value;
  }

- **Universal Selector:**
  ```css
  * {
    property: value;
    }

## Box Model

- **Width and Height:**
  ```css
  width: value;
  height: value;

- **Margin:**
  ```css
  margin: top right bottom left;
  
- **Padding:**
  ```css
  padding: top right bottom left;
  
- **Border:**
 ```css
  border: width style color;

### Typography

- **Font Family:**
  ```css
font-family: 'Font Name', sans-serif;

Font Size:
font-size: value;

Font Weight:
font-weight: normal | bold;

Text Alignment:
text-align: left | center | right;

Color
Color:
color: #RRGGBB;

Background Color:
background-color: #RRGGBB;

Layout
Display:
display: block | inline | inline-block | flex | grid;

Position:
position: static | relative | absolute | fixed;

Flexbox:
display: flex;

Grid:
display: grid;

Flexbox Properties
Flex Container:
display: flex;

Flex Direction:
flex-direction: row | column | row-reverse | column-reverse;

Justify Content:
justify-content: flex-start | flex-end | center | space-between | space-around;

Align Items:
align-items: stretch | flex-start | flex-end | center | baseline;

Transition and Animation
Transition:
transition: property duration timing-function delay;

Keyframes Animation:
@keyframes animation-name {
  0% { property: value; }
  100% { property: value; }
}

animation: animation-name duration timing-function delay iteration-count direction fill-mode;

Miscellaneous
Box Shadow:
box-shadow: h-offset v-offset blur spread color;

Opacity:
opacity: value; /* 0.0 to 1.0 */

Z-Index:
z-index: value;

Overflow:
overflow: visible | hidden | scroll | auto;

Cursor:
cursor: pointer | default | text | grab | not-allowed;


