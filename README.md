# reading-notes

Reading notes for Code 102!

Go to [Markdown Notes](rn01-markdown.md)

## Growth Mindset :thinking:

![A butterfly growing](https://images.unsplash.com/photo-1535231540604-72e8fbaf8cdb?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1774&q=80)

A growth mindset is *essential* to personal development. It's the ability to take a positive, can-do attitude, especially when facing unfamiliar tasks or trying to learn a new skill. To give an example from my personal life, many people see being artistic as an inborn talent - I know this isn't true, it's just that most artists started young and kept going. It's persistence and **focused** practice that lead to great work, not an innate ability. 

However reading through the article, I related to the authors tendency to sometimes throw his hands up and avoid the issue. To try and improve my own growth mindset, especially at this essential time where I'm beginning a tough course, I need to remind myself of the following: 

> - It's okay to get criticism. While it can feel a bit painful in the moment, constructive criticisms is just someone trying to help you push your abilities to their best. Take a breath and properly think about what they said. 
> * Try to find inspiration in others - I always feel more motivated when I see peers create something new, or interesting projects on the internet. I feel the urge to prove to myself I can do that too! Even if it may take slightly longer, it's always a good learning exercise. :) 
> + Learning anything is a physical process! When you begin learning something, the strength of your neural pathways is low, but repetition tells your body "this is important" and things like myelin production will increase. Myelin is responsible for 'insulating' your axons, and the presence of it allows your brain to transmit impulses much faster then 'un-myelinated' axons. 


## Read 01 - Learning Markdown 

Learning Markdown now will help me in the future as I create reading notes for other modules. Being able to organise my notes and easily quote code will make the learning process much easier. Github pages also allows me to access them from anywhere, which is just a *little* conveniant. **There are many markdown applications, although most of them generally support the same syntax.**

#### Markdown Basic Syntax
To make something bold use `**` on either side of the **text**

The `#` sign is used for creating headers. If you want to make a `<h3>` tag like in html, you use the corresponding number of `#`s.

To create a code block use a single tab (or four spaces if you just love pressing the space button). 

To show something is a peice of code, you can use back-ticks. Like I did above! ``Use double`back`ticks if you want backticks in your code example. Backtick inception!``

`***`, `___` and `---` can be used to make a horizontal line. 

You can even show colours: `#DC143C` although this only works in issues, pull requests and discussions on GitHub. 

#### Github Pages

GitHub pages is an easy way to host and share websites for projects, organisations and resumes. The source files for the sight will come straight from your repository. Keep in mind, even if your repo is private, the pages website will be public. 

## Things I want to know more about

Useing Jekyl themes for Pages and creating a small website for all my learning notes. I'm also trying to get used to flex and gridbox this week! I also want to get a basic understanding of what a framework like React.js accutally does (right now I think it's like a library of code?) and also what as static site generator is and how to use one. 

##### Static Sites vs Dynamic Sites. 

Satic Sites are the same for whatever viewer looks at them - like this one! You could think of it as a 'read-only' site. While it can be interactive and have animation, the users *actions* cannot change the site. They require minimal back end processing, as most things tend to be rendered client-side. 

A dynmaic site changes 


Git tags - look up. Git revisions - tags allow for names. 

## A quick overview of some web concepts and modern development. 

Besides the front-end trinity of HTML, CSS and Javascript, I'm finding myself generally confused by a lot of the terms I see online. React? Tailwind? API's? 

![Confused](https://media.tenor.com/xRWvL0QHJuoAAAAM/hmm.gif)

#### Some history: THIS IS WRONG FIX

> - Web 1 - Basic html and css files. Really ugly. Websites are static. 
> * Web 2.0 - User interaction
> + Web 3.0(?) - Ai driven. Unqiue experinces per user. 

#### HTML and CSS are the building blocks of web development.

- HTML5 Basic and Semantic tags 
- CSS Fundamentals
- CSS Alignment (Flexbox and Grid)
- Media Queires/Responsive Design - Make your website work on different devices. 
- Simple Animations / Transitions 

#### Extra tools. 
Sass is a pre-processor that adds some functionality to CSS. Variables, nesting, functions etc. Compile with a Sass compiler down to css. 
PostCSS a tool for transforming CSS with JavaScript.

#### CSS Frameworks. 

CSS frameworks give you predefined classes/components to style elements. This can speed up the project. Like using a primitive in maya instead of starting with the quad-draw tool. 

High level, like boostrap, means it comes with classes like `button` or `alert`, and these classes will contain many styles. Tailwind, beging low-level has many classes that do one one specific thing - like a class for verticle alignment. 

- **Bootstrap 5** - Popular, high level framework
- **Tailwind** - Low-level, utlity based framework. 
- **Materialize** - Based on material design (google?)
- **Bulma** - Mobile-first, modular. 
- **Foundation** - Bit older, advanced CSS framework. 

Frameworks are easy ish to learn once you know one. 

---

#### UI Design Principles
- **Color and Contrast** - Is the text readable?
- **Whitespace** - Check space between elements
- **Scale** - Relative element sizing
- **Visual Hierarchy** - Order of importance - Composition!
- **Typogaphy** - Font/Typefact, sizing. 

---

#### Java Script

Javascript adds interactivity and dynamic functionality. Javascript is main language of browsers. 

- **Js Basiscs** - Data types, data structures, functions, loops
- **DOM** - Document Object Model - An interfact in the browser that treats HTML tags as nodes. Make something show or dispear, make a request for data, ect. 
- **Async JS** - We don't want the website to just stall while it waits for a request from the server. Asynchonus rendering - same as in 3D. Understand promises, .thn, .wait, callbacks, .catch, 
- **Fetch API & HTTP** - Make Async server requests. Make requests to API's and understand HTTP. JSON - Javascript Object Notation. Common format for APIs. XML same thing. 
- **Array Methods** - map, filter, reduce, for each, etc. 

---

#### Other tools
- GIT - Version control. 
- NPM - Package manager to instal packages. Requires Node.JS - Look up. Node Package Manager. Packages - code that does a specific thing - framework, libraries. 
- Yarn - Same as NPM share the same repo's
- Markdown. Like this!
- Browser Dev tools
- IDE plugins - Emmet, Liver server, Prettier, ESLint, etc.

___

### Deploying Frontend Projects 

How do I deploy my project to the internet? 

Some popular platforms include: netlify, vercel, cPanel, amazonS3. 

For domain names - namecheap, Domain.com, bluehost, GoDaddy. 

To deploy a hosting platform -

GIT, SSH

---
 
**Web Design** - 
Learn more design
Get better at CSS
Simple Websites

**Frontend Framework** - Do this first! 
React, Vue, Svekte
Sate Managers
Server-Side Rendering

**Backend** 
Node.js, Python, PHP, C#, Go
Databases - Postgres, MonoDB
HTTP and API Development/ 

**Advanced JS**
Module Bundlers
Testing
Design Patterns

----

## Front End 
Some Frontend JS frameworks used for SPA's (Single Page Apps) The user only loads a single page, and then everything else is done through Javascipt, client side, and the UI is built from components. 

- React
    - Created by Facebook
    - Popular
    - Learning curve isn't terrible
    
Some things to learn with React - react router, jsx (create html in Javascript), Hooks, Context API Redux 

- Vue
    - Second most popular
    - Good community
    - Low learning curve
    
Some things to learn with Vue - Vue CLI, Vue Router, Composition API, Vuex 

- Angular
    - Made by google
    - Popular in enterprise
    - Steep learning curve
    
- Svelte
    - Lightweight Compiler
    - Low learning curve
    
----
#### TypeScript. 

Superset of Javascript - Basically it's Javascript with some extra stuff. 
- Static-Type Checking - JavaScript is not a typed language, meaning that when you define a variable or function, you don't have to specify the data type (string, interger, float, boolean etc) Typescript adds the option to add types to JS
- Class and Module Support
- Other ES6 features
- Code less prone to errors/Robust

#### UI kits

**Reusable design elements / components**

For React - Material UI, Onsen UI, Chakra UI, React Bootstrap. 
For Vue - Veutify, Buefy, Vue Material, Bootstrap Vue. 

## Testing

Unit Testing - Test blocks of code (functions, modules, classes) 

Integration Testing - Modules are combined and tested together

E2E Testing - Emulating a user. 

JS testing tools include, Jest, Cypress and Puppeteer.

## Server-Side Rendering 

We can render react, vue, front end frameworks on the server. 

This comes with some benefits, like improving SEO. Preformance benefits, routing is easier. 

**Frameworks** 
- Next.JS (Based on React) 
- Nuxt.JS (Based on Vue
       
