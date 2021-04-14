# JAVASCRIPT
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

>  **It is best to keep JavaScript code in its own JavaScript
file**

## STATEMENTS 

* **Statements should end with a semicolon**
Example
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

> JavaScript is a **CASE SENSITIVE** 

* **We can use comments  to explain what the code does**
> MULTI-LINE COMM ENTS we start with `/*` and end with `*\ `characters
> SINGLE-LINE COMMENTS we start with `//` anything that follows the two forward slash characters will not
be processed by JavaScript

## variables
the data stored in a variable can change each time a script runs. and we can assign a value to them.

## DATA TYPES 
1. Numeric Data `45`
2. String Data `'Hello, There'`
3. Boolean Data `true`

> **Example for Using variable to store a number**

```
var price;
var quantity;
var total;

price = 5;
quantity = 14;
total = price * quantity;

var el = document.getElementByid( ' cost ');
el .textContent = '$' +total; 









