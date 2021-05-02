## Domain Modeling

* Domain modeling is the process of creating a conceptual model in code for a specific problem. 

* Domain model thats design and build correctly  can verify and validate the understanding of the a problem.

* To define the properties between many object we want to use a constructor function and we can define it using **function expression** 

### Some tips to follow when building domain models :

1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.

2. Model its attributes with a constructor function that defines and initializes properties.

3. Model its behaviors with small methods that focus on doing one job well.

4. Create instances using the `new` keyword followed by a call to a **constructor function.**

5. Store the newly created object in a variable so you can access its properties and methods from outside.

6. Use the `this` variable within methods so you can access the object's properties and methods from inside.

## HTML Tables

### What is a table

* A table represents information in a grid format ,Grids allow us to understand complex data by referencing information on two axes 

* Examples of tables include financial reports, TV schedules, and sports results.

### Basic Table Structure

> The `<table>` element is used to create a table
>
> The start of each row we use `<tr>` tag
>
> and its It is followed by `<td>` tag 
>
> we use <th> element to indicate the heading for column or a row

```
<table>
 <tr>
 <td>15</td>
 <td>15</td>
 <td>30</td>
 </tr>
 <tr>
 <td>45</td>
 <td>60</td>
 <td>45</td>
 </tr>
 <tr>
 <td>60</td>
 <td>90</td>
 <td>90</td>
 </tr>
</table>
```
## JavaScript 

### Creating an Object 

* we can use the `new` keyword and the object constructor to create a blank object

* we can update the value of properties using the dot notation or square brackets
> `hotel.name = park` ( the hotel is object and `.name` is propery name and `park` property value

* We can create with properies and  methods :
1. literal notation 

```
var hotel = {
name: 'Quay' ,
rooms: 40,
booked: 25,
checkAvailability: function() {
return this.rooms - this .booked;
}
} ; 
```
2. object constructor notation

```
function Hotel(name, rooms, booked) {
this.name = name;
th is.rooms = rooms;
this.booked = booked;
this.checkAvailability = function()
return this.rooms - this.booked;
} ;
var quayHotel =new Hotel('Quay', 40 , 25);
var parkHotel =new Hotel('Park', 120, 77);
```


### Storing Data 

* In JavaScript, data is represented using name/value pairs. To organize the data, we can use an array or object to group a set of
related values. In arrays and objects the name is also known as a key

> * A variable has just one key (the variable name) and one value

> * Arrays can store multiple pieces of information. 

### Build in Object 

* Browsers come with a set of built-in objects that represent things like the browser window and the current web page shown in that window. These
built-in objects act like a toolkit for creating interactive web pages.

* JavaScript has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality 
that help you write scripts