# Forms

* The form is the box that can be in the website that collect data or using it to search or registering as a member of a website

## types of form

1. Adding text
> * Text input Used for a single line of text such as email addresses and names
> * Password input Like a single line text box but it masks the characters entered
> * Text area (multi-line) For longer areas of text, such as messages and comments

2. Making Choices
> * Radio buttons For use when a user must select one of a number of options
> * Checkboxes When a user can select and unselect one or more options
> * Drop-down boxes When a user must pick one of a number of options from a list

3. Submitting Forms
> * Submit buttons To submit data from your form to another web page
> * Image buttons Similar to submit buttons but they allow you to use an image

4. Uploading Files
> * File upload Allows users to upload files to a website

#### Forms work when user fills in a form and then presses a button to submit the information to the server

## Form Structure

* we Structure the form using the `<form>` element

* Every `<form>` element requires an `<action>` attribute

* Forms can be sent using one of two methods `ge`t or `post`

* HTML5 introduces new form elements which make it easier for visitors to fill in forms

# CSS style for list and tables and forms

* The `list-style-type` property allows to control the shape or style of a bullet point it can be used to rules that
apply to the `<ol>` `<ul>` and `<li>` elements like decimal or lower-alpha for Ordered Lists and disc or square for
Unordered Lists

* we can specify an image to act as a bullet point using the `list-style-image` property

* the `list-styleposition` s property can take one of two values to y indicates whether the marker should appear on the inside 
or the outside

* table properties

> * `width` to set the width of the table
> * `padding` to set the space between the border of each table cell and its content
> * `text-transform` to convert the content of the table headers to uppercase
> * `letter-spacing` font-size to add additional styling to the content of the table headers
> * `border-top`, `border-bottom` to set borders above and below the table headers
> * `text-align` to align the writing to the left of some table cells and to the right of the others
> * `background-color` to change the background color of the alternating table rows
> * `:hover` to highlight a table row when a user's mouse goes over it

* Forms are easier to use if the form controls are vertically aligned using CSS

* Forms benefit from styles that make them feel more interactive


# EVENT

EVENTS happend when a user interacts with the browse to trigger a function the code 

## How event work to trigger a javascript code 

* When the user interacts with the HTML on a web page, there are three steps to trigger some JavaScript code :
> 1. Select t he element node  you want the script to respond to
> 2. Indicate which event on the selected node(s) will trigger the response
> 3. State the code you want to run when the event occurs

Event Summry 

* Events are the browser's way of indicating when something has happened

* Binding is the process of stating which event you are waiting to happen, and which element you are waiting for that event to happen upon

* When an event occurs on an element, it can trigger a JavaScript function.

* You can use event delegation to monitor for events that happen on all of the children of an element

* The most commonly used events are W3C DOM events