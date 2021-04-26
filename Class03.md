# HTML List

##  HTML provides three type of list
* Ordered lists
> ordered list is created with the `<ol>` element and use number for the list
> every item is placed in a list with opening tag `<li>` and closing tag `</li>`

#### example

```
<ol>
<li>first</li>
<li>seconed</li>
<li>third</li>
</ol>
```

> and the result
> 1. first 
> 2. second
> 3. third

* Unordered lists
> unordered list is created with the `<ul>` element and use bullets for the list
> every item is placed in a list with opening tag `<li>` and closing tag `</li>`

#### example

```
<ul>
<li>first</li>
<li>seconed</li>
<li>third</li>
</ul>
```
> and the result
> * first 
> * second
> * third

* Definition lists
> The definition list is created with the <dl> element and we used it to define terminology 
> Inside the <dl> element we use <dt> and <dd> elements.

## Lists can be nested inside one another

# HTML Boxes

* Control the dimensions of the box 

> By default a box is sized just big enough to hold its contents. To set your own dimensions for a box you can 
> use the height and width properties we can use pixels, percentages, or ems to specify the size of a box

* Overflowing Content
> The overflow property tells the browser what to do if the content contained within a box is larger
> than the box itself. It can have one of two values :
> 1. hidden : This property simply hides any extra content that does not fit in the box
> 2. scroll : This property adds a scrollbar to the box so that users can scroll to see the missing content

* Border, Margin and Padding

> 1. Border : every box has a border that separates the edge of one box from another 
> 2. Margin : sit outside the edge of the border
> 3. Padding : is the space between the border of a box and any content contained within it

#### example 
![Border, Margin and Padding](https://sabe.io/classes/css/css-box-model-padding-border-margin/css-box-model.png)

* we can control the style of the box using the `border-style` property and can take the following values:
> `solid` a single solid line
> `dotted` a series of square dots
> `dashed` a series of short lines 
> `double` two solid lines
> `groove` appears to be carved into the page
> `ridge` appears to stick out from the page
> `inset` appears embedded into the page
> `outse`t looks like it is coming out of the screen
> `hidden / none` no border is shown

* we can specify the color of a border using either RGB values, hex codes or CSS color names
* we can center any content in the `HTML` using `CSS` for example :
> center a box using the left-margin and right-margin to auto.
* we can use `display`y property allows you to turn an inline element into a block-level or block-level to inline

* CSS3 has introduced the ability to create image borders and rounded borders.

# Basic Javascript

* A script is made up of a series of statements. Each statement is like a step in a recipe that contain very precise instructions

* Variables are used to temporarily store pieces of information used in the script

* Arrays are special types of variables that store more than one piece of related information.

* JavaScript distinguishes between numbers (0-9), strings (text), and Boolean values (true or false)

* Expressions evaluate into a single value and rely on operators to calculate a value

## SWITCH STATEMENTS

* the if... else statment check a condition if it true will run the first code block if it false will run the second code block 

![if else statment](https://cdn.programiz.com/sites/tutorial2program/files/js-if-else-if-statement_0.png)

* switch statement starts with a variable called the `switch value`. Each case indicates a possible value for this variable and the
code that should run if the variable matches that value.

![switch statment](https://www.theengineeringprojects.com/wp-content/uploads/2020/01/Switch-Statment-in-JavaScript-1.jpg)

* the purpose of the switch statement is to present the user with a different message depending on which level they are at

## TRUTHY and FALSY VALUES

* every value in JavaScript can be treated as if it were true or false

> **Falsy** values are treated as if they are false.
> **Truthy** values are treated as if they are true. Almost everything that is not falsy can be treated as if it were true
* All values evaluate to either `truthy` or `falsy` 

* **Logical operators** are processed left to right. They short-circuit (stop) as soon as they have a result 
but they return the value that stopped the processing **not necessarily true or false**

## LOOPS

> loops will check condition if it returns true a code block will run then the condtion will be checked again and will run the code block
again if its true and will not stop until the condition will returns a false

* tybe of loops

1. `FOR` to run the code for a specific number of time
2. `WHILE` dont know how many times to run the code and will run as long the condition is true
3. `DO WHILE` its the same as *WHILE* loop but the difference it will always run the statments inside the curly bracket at lease one time

* Loop counters to run the code for a specifid number of times 

![loop](https://media.geeksforgeeks.org/wp-content/uploads/Loop1.png)
