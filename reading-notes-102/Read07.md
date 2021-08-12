# CSS

* CSS create rules that specify how the content of an element should appear its like design the webpage.
* CSS Affect How Elements Are Displayed and its made of two part  a property and a value
**example** 
```
h1, h2, h3 {
font-family: Arial;
color: yellow;}

```
* we can use css with html
1. internal 
2. external
3. external style sheet

# Color 

* ** The color property allows us to choose the text color inside an element in three ways**
1. RGB Values
  **RGB stand for RED GREEN BLUE**
color can be set of how much red and green and blue are used to make the color example `rgb(100,100,90)`

2. Hex Codes

These are six-digit codes that represent the amount of red, green and blue in a color example `#ee3e80`

3. Color Name 

its a predefined color names that are recognized by browsers example `blue`

## Background Color

* **CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of 
the background for that box**

* we can use the three ways to choose color RGB,hex,color names

### Understanding Color

* **every color on a screen is created by mixing of red,green,blue**

* **computer monitors are made of pixels and every pixels color is mix of red,green,blue

## Opacity

* **the opacity property which allows you to specify the opacity of an element and any of its child elements.**
`The value is a number between 0.0 and 1.0`

* alpha allow you to add a fourth value to the **RGB --> (RGBA)** to indicate opacity.

## HSL Colors

* CSS3 bring a new way to specify new color using:

1. **HUE** is the colloquial idea of color. In HSL colors, hue is often represented as a color circle where the angle represents the
color, although it may also be shown as a slider with values from 0 to 360.

2. **saturation** is the amount of gray in a color.

3. **lightness** is the amount of white (lightness) or black (darkness) in a color.

### example ( COLOR)

```
<!DOCTYPE html>
<html>
<head>
 <title>Color</title>
 <style type="text/css">
 body {
 background-color: silver;
 color: white;
 padding: 20px;
 font-family: Arial, Verdana, sans-serif;}
 h1 {
 background-color: #ffffff;
 background-color: hsla(0,100%,100%,0.5);
 color: #64645A;
 padding: inherit;}
 p {
 padding: 5px;
 margin: 0px;}
 p.zero {
 background-color: rgb(238,62,128);}
 p.one {
 background-color: rgb(244,90,139);}
 p.two {
 background-color: rgb(243,106,152);}
 p.three {
 background-color: rgb(244,123,166);}
 p.four {
 background-color: rgb(245,140,178);}
 p.five {
 background-color: rgb(246,159,192);}
 p.six {
 background-color: rgb(245,176,204);}
 p.seven {
 background-color: rgb(0,187,136);}
 p.eight {
 background-color: rgb(140,202,242);}
 p.nine {
 background-color: rgb(114,193,240);}
p.ten {
 background-color: rgb(84,182,237);}
 p.eleven {
 background-color: rgb(48,170,233);}
 p.twelve {
 background-color: rgb(0,160,230);}
 p.thirteen {
 background-color: rgb(0,149,226);}
 p.fourteen {
 background-color: rgb(0,136,221);}
 </style>
</head>
<body>
 <h1>pH Scale</h1>
 <p class="fourteen">14.0 VERY ALKALINE</p>
 <p class="thirteen">13.0</p>
 <p class="twelve">12.0</p>
 <p class="eleven">11.0</p>
 <p class="ten">10.0</p>
 <p class="nine">9.0</p>
 <p class="eight">8.0</p>
 <p class="seven">7.0 NEUTRAL</p>
 <p class="six">6.0</p>
 <p class="five">5.0</p>
 <p class="four">4.0</p>
 <p class="three">3.0</p>
 <p class="two">2.0</p>
 <p class="one">1.0</p>
 <p class="zero">0.0 VERY ACID</p>
</body>
</html>
```


