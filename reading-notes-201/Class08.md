# Layout

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

### Screen Sizes 

* Different visitors to your site will have different sized screens

* The size of a user's screen affects how big they can open their windows and how much of the page they will see.

* Screen Resolution refers to the number of dots a screen shows per inch.

* designers often try to create pages of around 960-1000 pixels wide for the page size Because screen sizes and display resolutions vary so much

* Fixed width layout designs do not change size as the user increases or decreases the size of their browser window

* Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window

### Summary

* `<div>` elements are often used as containing elements to group together sections of a page

* The float property moves content to the left or right of the page

* Pages can be fixed width or liquid layouts

* You can include multiple CSS files in one page