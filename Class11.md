# Images

#### we can control the size of an image using the width and height properties in CSS

```
img.large {
width: 500px;
height: 500px;}
img.medium {
width: 250px;
height: 250px;}

```

* Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images

#### Aligning images using CSS

* we can use float property to move an element to the left or the right of its containing block

```
img.align-left {
float: left;
margin-right: 10px;}
img.align-right {
float: right;
margin-left: 10px;}

```
* centering images 

> * there are two common ways to center an image
> 1. On the containing element, we can use the text-align property with a value of center
> 2. On the image itself, we can use the margin property and set the values of the left and right margins to auto.

#### Background Images

* The background-image property allows to place an image behind any HTML element

```
body {
background-image: url("images/pattern.gif");}

```

* background-repeat property can have four values
> 1. `repeat`
> 2. `repeat-x`
> 3. `repeat-y`
> 4. `no-repeat` can have one of two values, `fixed` and `scroll`

* we use the `background-position` property to specify where in the browser window the background image should be placed
> This property usually has a pair of values like `left top` , `left center`

* We can create image rollover effects by moving the background position of an image

### HTML video and audio

* The `<video>` and `<audio>` elements allow us to embed video and audio into web pages for example

```
<video controls>
  <source src="rabbit320.mp4" type="video/mp4">
  <source src="rabbit320.webm" type="video/webm">
</video>

```

# Practical Information

#### Search Engine Optimization (SEO) : 

* SEO is the practice of trying to help your site appear nearer the top of search engine results 

* On-page techniques are the methods you can use on your web pages to improve their rating in search engines

> * there are seven key places where keywords can appear in order to improve its findability :
> 1. Page Title
> 2. URL / Web Address
> 3. Headings
> 4. Text
> 5. Link Text
> 6. Image Alt Text
> 7. Page Descriptions

* Analytics tools such as Google Analytics allow to see how many people visit your site, how they find it,
and what they do when they get there

* To put your site on the web, you will need to obtain a domain name and web hosting

* File Transfer Protocol allow to transfer files across the Internet from local computer to the web server hosting your site