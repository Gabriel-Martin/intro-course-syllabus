# Night 1: HTML & CSS

## 1. HTML

- What is HTML?
  - Hypertext Markup Language
  - Markup language to give content structure and meaning.
- Elements, Attributes & Tags

  - Elements
    - HTML components that define the specification of the content to be structured.
    - Examples:
      - body
      - h1-h6: Used for creating headings from most important (h1: large text) to least important (h6: small text).
      - p
      - div: A container element that wraps other elements.
      - img
      - a: Anchor tag. Used as a link to other webpages.
      - ul / ol
      - li
  - Attributes
    - Additional information provided to the given element.
    - Examples:
      ```html
      id=”avatar”
      class=”button”
      href=”https://www.google.com”
      ```
  - Tags
    - Encompass the element and their corresponding attributes.
    - Examples:
      ```html
      <body id=”root”>Content</body>
      <a href=”https://www.devtree.io”>Link</a>
      <img src=”./my-image.png” />
      ```
  - Block vs Inline Elements
    - Block Level
      - Begin on a new line within the document and occupy the full available width.
      - Examples:
        - header
        - div
        - p
    - Inline Level
      - Do not begin on a new line with the document, and only occupy the necessary width required by their content.
      - Examples:
        - a
        - img
        - span
        - Input
  - Document Structure
    - DOCTYPE
    - html
    - head
    - body

---

## 2. CSS

- What is CSS
  - Cascading Style Sheets
  - Presentation language to give content style and appearance.
- Selectors, Properties & Values
  - Selectors
    - Determines which element to apply the style to.
    - Examples:
      ```css
      header {
        property: value;
      }
      body > div {
        property: value;
      }
      ```
  - Properties
    - Determine style that will be applied to the element
    - Examples:
      ```css
      selector {
        color: value;
      }
      selector {
        margin: value;
      }
      ```
  - Values
    - Determines the behavior of the style applied
    - Examples:
      ```css
      selector {
        property: blue;
      }
      selector {
        property: 10px;
      }
      ```
  - CSS Selectors
    - Element
      - Targets by the element's name.
      - Examples:
        ```css
        elementName {}
        <elementName />
        ```
    - Class
      - Targets by the element's classname.
      - Used to group student
      - Examples:
        ```css
        .elementClassName {}
        <element class=”elementClassName” />
        ```
    - ID
      - Targets by the element's unique ID.
      - Examples:
        ```css
        #elementID {}
        <element id=”elementID” />
        ```
  - CSS Box Model
    - width
    - height
    - padding
    - margin
    - Box-sizing

---

## Project:

> Build a simple profile page using HTML & CSS.  
> This project will be instructor lead.
