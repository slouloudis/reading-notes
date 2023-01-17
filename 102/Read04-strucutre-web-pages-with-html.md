# 04 Structure web pages with HTML


## Wireframes and Design

Like from my art days, a wireframe serves the same purpose as a thumbnail image - a low fidelity 'test run' of what you want the webpage to be structured like. We're not focusing on images,font choice or fancy design - just what the barebone layout of the website will be like for the user. 

**Some things to keep in mind**

- Try to figure out how many pages in total your website is going to be. What is the users flow through the website like?

- Sketch, don't illustrate. We're doing concept design, not a poster illustration ;)

* Keep it simple. People don't remember most designs, but they will complain about bad ones. Don't let a user click off your page because its a nightmare to navigate around. 

## HTML 

HTML is a *markup language*, the same way this file is written in *markdown*

An HTML document consists of elements, which have tags wrapped around them. 

`<h1 class="coolClass">Wow this is great!</h1>`

^ The above is an element. It consist of the opening tag, any class or ID assignments (**attributes**), the content itself, and the closing tag. 

¬ The below is a 2 tags, the second to close the tag we opened with /

`<h1></h1>` 

Attributes like `class="className"` will always have an attribute (in this case `class`, an `=` and an attribute assignment like `className`)

## Structure

HTML elements tend to go `<head>` containing meta information about the site and then `<body>` containing things the user will see. 

inside the body, generally websites will have a header, sections, and a footer. 

## Some tags

I'm not going to list the tags I'm using very often, just ones I might forget about. 

#### **Links**

`<a href="www.link.com">My Link</a>`

    a stands for anchor. sometimes. in the above anyway. it could stand for anything, if you think about it.

## Being correct, semantically 

Basically, just name stuff corresponding to what is it on your page. If it's a very important header, its the raison d'etre of your website, slap an h1 tag on it. If it's a section, call it a section, and if it's a link, don't call it a link, call it a href. Simple! 

It doesn't matter if you want some other text on your website to **look** bigger than your h1 tag. That's for CSS. HTML is all about what's under the skin. 

It's important to do this for screen readers, SEO, and helping other people read what's going on. 

Some useful ones are:

```
<aside>
<header>
<mark>
<section>
<summary>
<time>
<main>
<article>
<nav>
```
There are more, but go read the docs. 