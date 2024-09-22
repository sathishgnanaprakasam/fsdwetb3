# Additional Session - Doubts

## Doubts

- [x] Positioing - Relative and Absolute
- [x] Media Queries
- [x] Setting up the background with an image [https://trbook.netlify.app/](https://trbook.netlify.app/)
- [x] Installing Fonts - Google Fonts - Poppins
- [x] Flexbox
- [x] Z-Index
- [x] Grid - Layout
- [x] Using multiple classes in CSS

## Notes

### Positioning - Relative and Absolute

- When a position of an element is set to either relative or absolute, we can use the top, bottom, left, and right properties to move the element from its original position.

- When the position is set to relative, The element will be placed relative to the document's normal flow. If the element is moved from its original position, the space is still reserved for the element.

- When the position is set to absolute, The element will be placed relative to the nearest positioned ancestor. If there is no positioned ancestor, the element will be placed relative to the initial containing block. The element will be removed from the normal flow and the space will not be reserved for the element.

### Media Queries

- Media queries are used to apply different styles for different devices based on the device's width, height, orientation, etc.

Example:

992px is the breakpoint for a medium-sized device. For >= medium-sized devices, the navigation bar should be displayed as a flexbox.

For 991px and below, the navigation bar will be hidden and a hamburger icon will be displayed.

### z-index

- The z-index property specifies the stack order of an element.
- An element with a higher z-index will be displayed in front of an element with a lower z-index.

# Session - Tailwind CSS

## Contents

- [x] Setup
- [x] Typography
- [ ] Borders
- [ ] Customization
- [ ] Colors
- [ ] spaces & sizes
- [ ] Images

## Notes

### Context

- Tailwind CSS is a utility-first CSS framework for rapidly building custom designs.

Library: Library is a collection of pre-built classes that can be used to style the elements.
Framework: Framework is a collection of libraries that can be used to build the application.

- Websites: Business owners will want to set a visually appealing website and a creative website to attract more customers and to setup a brand image.
- Web Applications: [ERP, CRM, etc.]: Business owners does not care about the design of the application. They care about the functionality of the application.

### Tasks

1. Typography

- Create a heading with a font size of 4xl and bold weight.
- Add a paragraph with a smaller text and italic size.
- Create two additional paragraphs with different text colors (blue and red).
- Center align the heading and right align the paragraphs.
- Add a letter spacing of 2px to the paragraphs.
- Add a line height of 1.5 to the paragraphs.
