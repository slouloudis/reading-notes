# Grid and Flexbox

Flexbox is designed for one-dimensional content. Explain what this means.
*Items will flex along the main axis: set by the user. All the items move along one dimension. Compare to grid, were the items displayed two-dimensionally: along the Colum and grid.*
Explain the difference between the main axis and cross axis.
*Some important ideas - Flex is a 2D layout module - we're 'flexing' items across their main axis and perpendicular to their cross axis. Our main axis can be horizontal or vertical. Ie - 'x' doesn't have to be our main axis, 'z' could be. Essentially the cross axis is the 'other' axis.*
How can using certain properties of flexbox negatively impact accessibility?
Screen readers will read the semantic content of the website, which may not match up with the visuals of it. Things like `row-reverse` will reverse a list of elements visually, but not affect how screen readers see them.
---
Flexbox is designed as a system for displaying various content - it has way more options, its way more robust, and it offers a better developer experience. Float was designed to emulate newsprint layouts and just isn't as powerful as flexbox.

Flex box is important to my career goals as I doubt I would get hired if I said I didn't know how to do it.

## Flexbox

Flex items only flow in one direction - your layout may *look* like it has two dimensions (rows and columns) but flex items can only flow in one direction: along the main axis.

The flex items are flexed in their direct parent container - the flex box.

### Flex Containers

Their possible properties:

- flex-direction - sets the direction of the main axis. Is your main axis the x or z axis?

- flex-wrap - by default, flexbox will try to set all elements into one row. turning flex-wrap off with stop this behaviour

- flex-flow - a combined property for both flex wrap and flex direction. Writing `flex-flow: column wrap;` is the same as writing `flex-direction:column;` & `flex-wrap: wrap;`

- justify-content - defines how flex items are laid out along the main axis - ie centre will try to lay items out centrally on the main axis

- align-items - same as justify content but works on the cross axis.

- align-content - If you've used the `flex-wrap` property on the container, you can use align-content to align all of the flex items as a unit. Used on multi-line flex containers. Think about affecting all of the flex items as if they are a single item.

### Flex Items

Flex items, the direct children of the flex container element, also have properties just for them.

```
<div class="flex-container">
    <h2 class="flex-item">Item 01</h2>
    <h2 class="flex-item">Item 02</h2>
    <h2 class="flex-item">Item 03</h2>
</div>
```

- order - by default, flex items are laid out in the source order. eg, above, everything would the items would be laid out as item 01 then item 02, and so on. Using the order property you can change the order in which elements appear without changing your DOM. This is useful if you want your html in a certain order for semantic reasons, but want them to display in a different order for design reasons. 

- flex-grow & flex-shrink - Consider the concept of available space: using these properties, we are changing the way the items fill the available space.

- flex-basis - size of the flex items before they are placed in a flex container. It controls the width and height along the main axis.

- flex (shorthand) - instead of using grow, shrink and basis, we can use a short hand of `flex: [grow] [shrink] [basis];` or, to reword `flex: [max] [min] [ideal size];`

- align-self - this can be applied to individual items. Used to align specific items differently to the other flex items. `align-self: strech;` is the default. Has the same options as align-content.