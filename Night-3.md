# Night 3: Flexbox Intro

## Flexbox

- What is flexbox?
  - Flexbox is a CSS layout spec that allows us to position HTML elements on a two-dimensional plain. (vertically or horizontally).

## Usage:

- Flex Container (parent)

  - display: Allows to define the display type of the container.

    - Values: none | block | inline-block | **flex** ...

  - flex-direction: Allow us to define the layout direction of items inside the container.
    - Values: row (default) | column | row-reverse | column-reverse
  - justify-content: Defines the placement of items on the primary axis of the container.
    - Values: flex-start | flex-end | center | space-around | space-between | space-evenly
  - align-items: Defines the placement of items on the secondary axis of the container.
    - Values: flex-start | flex-end | center | stretch

- Flex children
  - flex: Determines how the child will grow or shrink on the main axis inside the container.
  - Values:
    - flex-grow: A number specifying the how much the item can grow relative to other flex items.
    - flex-shrink: A number specifying how much the item can shrink relative to other flex items.
    - basis: The initial size of the item
  - align-self: Allows us to define how the item is aligned on the secondary axis of the container:
  - Values: auto | flex-start | flex-end | center | stretch

---

## Project:

> Build a simple layout using flexbox.  
> This project will be instructor lead.
