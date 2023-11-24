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
  Example : p { color: blue; }

- **Class Selector:**
  ```css
  .classname
  {
    property: value;
  }
  Example: .highlight { background-color: yellow; }

- **ID Selector:**
  ```css 
  #idname
  {
    property: value;
  }
  Example: #header { font-size: 24px; }
  
- **Universal Selector:**
  ```css
  * {
    property: value;
    }
  Example: * { margin: 0; }

- **Descendant Selector:**
  ```css
  ancestor descendant
  {
  styles
  }
  Example: article p { font-style: italic; }

- **Child Selector:**
  ```css
  parent > child
  {
   styles
  }

- **Attribute Selector:**
  ```css
  element[attribute="value"]
  {
   styles
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

## Typography

- **Font Family:**
  ```css
  font-family: 'Font Name', sans-serif;

- **Font Size:**
  ```css
  font-size: value;

- **Font Weight:**
  ```css
  font-weight: normal | bold;

- **Text Alignment:**
  ```css
  text-align: left | center | right;

## Color
- **Color:**
  ```css
  color: #RRGGBB;

- **Background Color:**
  ```css
  background-color: #RRGGBB;

## Layout
- **Display:**
  ```css
  display: block | inline | inline-block | flex | grid;

- **Position:**
  ```css
  position: static | relative | absolute | fixed;

- **Flexbox:**
  ```css
  display: flex;

- **Grid:**
  ```css
  display: grid;

## Flexbox Properties
- **Flex Container:**
  ```css
  display: flex;

- **Flex Direction:**
  ```css
  flex-direction: row | column | row-reverse | column-reverse;

- **Justify Content:**
  ```css
  justify-content: flex-start | flex-end | center | space-between | space-around;

- **Align Items:**
  ```css
  align-items: stretch | flex-start | flex-end | center | baseline;

## Transition and Animation
- **Transition:**
  ```css
  transition: property duration timing-function delay;

- **Keyframes Animation:**
  ```css
  @keyframes animation-name {
  0% { property: value; }
  100% { property: value; }
  }

  animation: animation-name duration timing-function delay iteration-count direction fill-mode;

## Miscellaneous
- **Box Shadow:**
  ```css
  box-shadow: h-offset v-offset blur spread color;

- **Opacity:**
  ```css
  opacity: value; /* 0.0 to 1.0 */

- **Z-Index:**
  ```css
  z-index: value;

- **Overflow:**
  ```css
  overflow: visible | hidden | scroll | auto;

- **Cursor:**
  ```css
  cursor: pointer | default | text | grab | not-allowed;

## Conclusion
This cheatsheet covers some fundamental CSS properties and values. Experiment and explore these to enhance the styling of HTML documents.

