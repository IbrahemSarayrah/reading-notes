# Text in HTML

**HTML elements are used to describe the structure of the page** like
> headings 
> paragraphs

## Headings and paragraphs
* **Headings**
HTML has six **levels** of headings:

> # <h1> </h1> `used for main headings`
> ## <h2> </h2> `used for sub headings`
> ### <h3> </h3> `used for sub headings`
> #### <h4> </h4> `used for sub headings`
> ##### <h5> </h5> `used for sub headings`
> ###### <h6> </h6> `used for sub headings`

* **Paragraphs**

> to create a paragraphs, surround the words with the p element with openning tag `<p>` and closing tag `</p>`
> By default, a browser will show each paragraph on a new line

* we can use more tags to structured the text and make it easier to read and more visibel to the user like :

> **bold** with the `<b>` element
> *italic* with the `<i>` element
> use superscript `<sup>` element and subscript `<sub>` element to contain contain characters for example

```
<p>On the 4<sup>th</sup> of September you will learn
 about E=MC<sup>2</sup>.</p>
<p>The amount of CO<sub>2</sub> in the atmosphere
 grew by 2ppm in 2009<sub>1</sub>.</p>

```

> and there are many element we can use to make the web page easier to read like whie space and line breaks

## The Semantic markup is :

a text elements that give information to the page about the content inside the openning tags and the closing tags like the

**p** element that indicate that the content inside is a paragraph and the browser will know how to show the paragraph ( the text elemets )

*some example of the semantic element:

> `<strong >`
> `<address>`
> `<article>`


# CSS

* CSS stands for **Cascading Style Sheets** and its control the design the layout of the web page its allowspecify how the content of
an element should appear

* CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look

* CSS works by associating rules with HTML elements, A CSS rule contains two parts: a `selector` and a `declaration` for exmaple

```
p {
 font-family: Arial;}

```
> the p is the selector
> the font family is the declaration
> inside curly brackets contain a property `font-family` and a value `Arial`

### we can use CSS with HTML in three ways :

1. internal inside the opening tag
2. external inside the <style> element
3. external style sheet by linking the HTML file with the CSS file using the `<link>` element

# Javascript

* a script is a series of f instructions that a computer can follow step by step every step known as a **statement**

* Statement are instructions and every statement start on a new line and can be organized into code blocks

* Statements should end with a semicolon Example

```
var today= new Date{);
var hourNow = today.getHours{) ;
var greeting;
if (hourNow > 18) {
greeting= 'Good evening';
else if (hourNow > 12) {
greeting= 'Good afternoon';
else if (hourNow > O) {
greeting 'Good morning';
else {
greeting 'Welcome';
document.write(greeting) ;

```

* We can use comments to explain what the code does

> MULTI-LINE COMM ENTS we start with /* and end with *\ characters SINGLE-LINE COMMENTS we start with // 
> anything that follows the two forward slash characters will not be processed by JavaScript

*JavaScript distinguishes between numbers (0-9), strings (text), and Boolean values (true or false)

### what is variables

* **the data stored in a variable can change each time a script runs. and we can assign a value to them.**

### DATA TYPES

1. Numeric Data

2. String Data

3. Boolean Data

### Arrays

* arrays is a special type of variable it can store a list of value 

* the numbering of this list in the arrays starts at zero 

### EXPRESSIONS

* Expressions evaluates into in a single value 

* there are two types of expressions:
1. Expressions that assign value to a variable
2. Expressions that use two or more values to return a single value

* Expressions rely on things called operators they allow to create a single value from one or more values

### type of operators 
* ARITHMETI C OPERATORS
* STRING OPERATOR

### Decision making

* there are places in the script where desisions are made that determine which line of code should run

* there are two components to a decision 
1. an expression is evaluated which returns a value
2. a conditional statment says what to do in a fiven situation

* we can compare one value in the script to what expect it will be the result will be boolean `true or false`

* logical operators return a single value of `true or false` and allow to compare the result of more than one comparison operator

* the if statment checks a condition that evaluate to a `true or false` to run the block of code based on the condition
