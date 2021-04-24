# How people access the web
1. browsers : access website using software called a web browser examples like chrome and firefox
2. web servers : wen request made in a web page that request go to accross the internet to a special computer known as a web server
which host the website
3. screen readers : programs that read out the content of a computer screen to a user.

* ** the web work When you visit a website, the web server hosting that site could be anywhere in the world. In order for you to find 
the location of the web server, your browser will first connect to a Domain Name System (DNS) server.**

# HTML 

* **HTML** its **HyperText Markup Language** and its the structure of a web page
   
* HTML use **elements** usually made up of two tags openning and closing tags the closing tag has an extra forward slash in it

* HTML Uses Elements to Describe the Structure of Page like the heading:

> `<h1> Heading </h1>`
>
> `<h3> sub-Heading </h3>`

Tags act like containers, as they tell information about what inside them

* the attributes tell more about the elements and they are in the opening tag of the element and are made up of two parts:
a **name and a value**

```
<p lang="en-us">Paragraph in English</p>

lang is the name of the attribute and the ( en-us ) is the value of the attribute

```
## HTML5 Layout 

* **HTML5 elements indicate the purpose of different parts of a web page and help to describe its structure.**

* **The new elements in html5 indicate what the content inside the element like in <article>**

### The elements in HTML5

* DOCTYPES tell the browser which version of HTML you are using

* X You can add comments to your code between the '<!-- and -->' markers.


* Headers & Footers that appears at the top or bottom of every page
>  <header> <footer>

* Navigation *contain the navigation bar on website*

> <nav> 

* Articles The element acts as a container for any section of a page we can use it with the <p> and <img> elements

> <article>

* Aside when we use it inside the <articls> element will contain information that is related to the article and when use out of the 
  articles will contain information for the all the site sections 

> <aside>

* Sections  groups the related content together

> <section>

* Heading Groups to group a set of one or more h1 to h6

>  <hgroup>

* Figures It can be used to contain any content that is referenced from the main articles

> <figure> <figcaption> 

> The id and class attributes allow  to identify a selected element
>
> The <meta> tag contain information about the site

### example of HTML5 layout  [HTML5](https://i0.wp.com/www.silocreativo.com/en/wp-content/uploads/2014/02/html5-structure-web.jpg?resize=390%2C569&quality=100&strip=all&ssl=1)

## Process & Design

1. the site should be designed for a target audience its important to understand the audience the site is for
2. the reason why people vist the site what are the motivation and goals of the site and what are they trying to achieve
3. make sure the audience have the information that they need when visting the site to achieve their goals quickly and effectively
4. how often people Will Visit Your Site gives an indication for how often you should update the site

# Javascripts

* Javascript make web page more interactive with :
1. access content javascript can select any element attribute or text from HTML page
2. modify content by adding element attribute and text to the page
3. program rules by specify a set of steps for the browser to follow which allow it to access or change the content
4. react to events by specify the script should run when a specific event has occurred

## What is a script

* A script is a series of instructions that a computer can follow step by step to achieve a goal. 
* browser may use different parts of the scripts depending on how the user interacts with the web page
### to write a script we need :

1. define the goal (the task ) we want to achieve
2. design the script by split the goal into series of task
3. code each step by writen them into programming langaue that computer understand with javascript

## how computers fit in the world around them :

* computers create models of the world using data, the computer use the data to follow the task that the user give it to the computer

* the object can represent physical things and can have properties like value and name that tell information about the object

* programmers choose which code to run when a specific event happens that event can use a specific section of the code 

* methods are The code for a method can contain lots of instructions that together represent one task

**Computers use data to create models of things in the real world. The events, methods, and properties of an object all relate to 
each other: Events can trigger methods, and methods can retrieve or update an object's properties**

### How JAVASCRIPT and HTML AND CSS fit TOGETHER
* The HTML gives the page structure  `(THE CONTENT LAYER)`
* The CSS is the design for the HTML and state how content is presented `(THE PRESENTATION LAYER)`
* The JAVASCRIPT will add interactivity to the web page `(BEHAVIOR LAYER)`

> #### JavaScript is written in plain text Like HTML AND CSS with **.js** file extension

### - **Linking a JavaScript From HTML page we use `<script>` element** to tell the browser its a JavaScript.

### Example 
```
<!DOCTYPE html>
<html>
<head>
<title>Constructive &amp; Co.</ title>
<link rel ="stylesheet" href="css/ cOl.css" />
</ head>
<body>
<hl>Constructive &amp ; Co. </ hl>
<script src="js/ add-content.js"></ script>
<p>For all orders and i nquiries please cal l
<em>SSS-3344</ em></ p>
</ body>
</html>
```
* **JavaScript runs where its is found in the HTML**

* **When the browser comes across a `<script>` element, it stops to load the script and then checks to see if it needs to do anything.**

>  **It is best to keep JavaScript code in its own JavaScript file**







