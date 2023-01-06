---
title: rn4me-cssBasic
filename: rn4me-cssBasic-markdown.md
--- 

# CSS Notes!

Place to store information about CSS. 

## The C in CSS - Managing Specificty 

What is the cascade.  
The cascade is an algorithm for solving conflicts when multiple styles are applied to the same html element. Assumming you do the following:

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

# Layout, positioning, aligment - how do we move thing about?

### Box model review 


## Grid & Flexbox.

# Advanced Selectors & Properties

## CSS Variables. 

## Psuedo Classes & Selectors

Psuedo selectors are special selectors used commonly in interactivity in the website. Used a lot in animation and transitions. There are a few key psuedo selectors:

```
An example: h2:hover {
              color:red;
            }
```
`hover` will make the h2 red when the mouse hovers over it. 

Some useful Psuedo selectors: 

```
[tag]:first-child/last-child;
[tag]:nth-child(n); - (2) would select every second child
[tag]only-child; for every [tag] that only has one child, will change property. 
```
**Keep in mind, if you have a `ul` nested in an `li` you need to select the `ul` tag to use the Psuedo selectors above, - think child of the tag, not child of the block.**

# Color, Image, and other shiny things

# Typography & Font manipulation

# Animation & Transitions 
