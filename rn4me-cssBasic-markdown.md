---
title: rn4me-cssBasic
filename: rn4me-cssBasic-markdown.md
--- 

# CSS Notes!

Place to store information about CSS. 

## The C in CSS - Managing Specificity 

What is the cascade.  
The cascade is an algorithm for solving conflicts when multiple styles are applied to the same html element. Assuming you do the following:

```
body{
  colour:green;
}
body{
  colour:red;
}
body{
  colour:yellow;
}

```
Our selector `body` is being called three times with different colours. CSS will 'cascade' down the document and use the last property assigned - yellow. 

However, there is another concept called specificity. For example:
```
h1{
  colour:red;
}

body{
  colour:green;
}

```
Here, even though the green body property is the last selector, the `h1` selector is more specific than `body`, so any `h1` elements will be red.  Your selectors can be more or less specific. 

**Some new tech - CSS Cascade Layers**

# Layout, positioning, alignment - how do we move thing about?

### Box model review 

A browsers rendering engine represents each element as a rectangular box. We can use CSS to change the style, size, position etc of theses boxes. All boxes consist of the following:

- Margin (Edge)
- Border (Edge) 
- Padding (Edge)
- Content (Edge)

The content edge is the width and height of the 'real' content. 

####

There are several layout modes, the default being *Normal Flow* Normal Flow consists of Block and Inline elements. 
Table, Float, Positioned & Multi-column layout. 
I'll be focusing on *Grid* and *Flexbox*

**Not all CSS properties work on all layout modes!!! They can be unique to their specific layout mode**

## Grid & Flexbox.

# Advanced Selectors & Properties

## CSS Variables. 

## Psuedo Classes & Selectors

Pseudo selectors are special selectors used commonly in interactivity in the website. Used a lot in animation and transitions. There are a few key pseudo selectors:

```
An example: h2:hover {
              color:red;
            }
```
`hover` will make the h2 red when the mouse hovers over it. 

Some useful Pseudo selectors: 

```
[tag]:first-child/last-child;
[tag]:nth-child(n); - (2) would select every second child
[tag]only-child; for every [tag] that only has one child, will change property. 
```
**Keep in mind, if you have a `ul` nested in an `li` you need to select the `ul` tag to use the Pseudo selectors above, - think child of the tag, not child of the block.**

# Color, Image, and other shiny things

# Typography & Font manipulation

# Animation & Transitions 
