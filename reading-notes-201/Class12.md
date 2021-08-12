# Create Charts with CHART.JS

* Charts are better for displaying data
* They’re easier to look at and convey data quickly

### We Can use [ChartJs](https://www.chartjs.org/) a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page and the chart 
types we can make using chart js are : 

1. line chart
2. bar chart
3. radar chart
4. radar chart
5. doughnut and pie chart
6. polar area chart
7. bubble chart
8. scatter chart
9. area chart
10. mixed chart types

* [ChartJs](https://www.chartjs.org/) have the way how to Setting up chart in the website

## The `<canvas>` element

* The `<canvas>` element has only two attributes, `width` and `height`

* The `<canvas>` element can be styled just like any normal image

* Browsers that don't support `<canvas>` will ignore the container and render the fallback content inside it

*  the `<canvas>` element requires the closing tag `(</canvas>)`

## Drawing shapes with canvas

* we can use the canvas to draw shaps like  rectangles, triangles, lines, arcs and curves and we can use the canvas with **chart**

example 

```
function draw() {
  var canvas = document.getElementById('canvas');
  if (canvas.getContext) {
    var ctx = canvas.getContext('2d');

    ctx.fillRect(25, 25, 100, 100);
    ctx.clearRect(45, 45, 60, 60);
    ctx.strokeRect(50, 50, 50, 50);
  }
}

```

### Apply colors to a shape, there are two important properties we can use: `fillStyle` and `strokeStyle`

> fillStyle = color
>
> strokeStyle = color

example

```
ctx.fillStyle = 'orange';

ctx.strokeStyle = 'rgba(255, 0, 0, 0.5)';

```

### Draw text onto the canvas

* The canvas rendering context provides two methods to render text:
> 1. `fillText(text, x, y [, maxWidth])` : Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
>
> 2. `strokeText(text, x, y [, maxWidth])` :Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

* a `fillText` example

```
function draw() {
  var ctx = document.getElementById('canvas').getContext('2d');
  ctx.font = '48px serif';
  ctx.fillText('Hello world', 10, 50);
}

```

* a `strokeText` example

```
function draw() {
  var ctx = document.getElementById('canvas').getContext('2d');
  ctx.font = '48px serif';
  ctx.strokeText('Hello world', 10, 50);
}

```

* There are some more properties which let us adjust the way the text gets displayed on the canvas

> font = value
>
> textAlign = value
>
> textBaseline = value
>
> direction = value
