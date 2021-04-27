# HTML 

## Links

* Links are the defining feature of the web they allow us to move from one web page to another **the idea of browsing or surfing**

## How to write links :

* we use the <a> element the user can clock between the opening `<a>` tag  and the closing tag `</a> and specify which page the link go to
using the `href` attribute

![a-element](https://www.computerhope.com/jargon/h/html-tag.gif)

#### type of links:

> * Links from one website to another
> * Links from one page to another on the same website
> * Links from one part of a web page to another part of the same page
> * Links that open in a new browser window
> * Links that start up your email program and address a new email to someone
> * `We can use the id attribute to target elements within a page that can be linked to`

## Directory Structure

> On larger websites it's a good idea to organize your code by placing the pages for each different section of the site into a new folder. 
> Folders on a website are sometimes referred to as directories.

## Relative URLs 

> * we can use realtive URLs when linking to pages in the same website, They provide a shorthand way of telling the browser where to find your files

#### Realtive Links Types :

> * Same Folder `<a href="reviews.html">Reviews</a>`
> * Child Folder `<a href="music/listings.html">Listings</a>`
> * Grandchild Folder `<a href="movies/dvd/reviews.html">Reviews</a>`
> * Parent Folder `<a href="../index.html">Home</a>`
> * GrandParent Folder `<a href="../../index.html">Home</a>`

## Layout

* **CSS allow us to control the layout of the page and where each element sits on a page**

### Key Concepts in Positioning Elements:

* **Building Blocks** 

> CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

* **Containing Elements**

> If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

### Controlling the Position of Elements :

> CSS has the following **positioning schemes** that allow you to control the layout of a page :
> * `Normal flow` Every block-level element appears on a new line causing each item to appear lower down the page than the previous one.
> * `Relative Positioning` This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom,
> or left of where it would have been placed.
> * `Absolute positioning` This positions the element in relation to its containing element.
> * we may also use `box offset` to o indicate where a box should be positioned and tell the browser how far from the top or bottom
> and left or right it should be placed
> * `Fixed Positioning` This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element.
> * `Floating Elements` Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box. 

![layout](https://miro.medium.com/max/3392/1*ia4V5qfk6Ki3iWIn-SmErw.png)

## WHAT IS A FUNCTION?

> * Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, 
> you can reuse the function (rather than repeating the same set of statements). 

### Declaring a function 

> * when we create a function we five it a name after that we write the statment needed to achieve its task inside the curly brackets

### Calling a function 

> * after declaring the function we can exexute all the statements between the carly brackets with just one line of code the `FUNCTION NAME`

* **sometimes functions needs a specific information to performe its task and we give it a `parameters` inside the function**

* **when we call a function that have `parameters` we need to specify the values for it**

* **we can git a single value or multiple values out of a function**
