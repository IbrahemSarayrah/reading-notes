#### What does .map() return?

* will return an array as a result of calling the function for each element in the original array.

#### If I want to loop through an array and display each value in JSX, how do I do that in React?

* for example

```
const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li>{number}</li>
);

```

* we loop through the **numbers** array using the JavaScript **map()** function. We return a `<li>` element for 
each item. and we assign the resulting array of elements to listItems.

* **Each list item needs a unique key .**

* **key** : is a special string attribute you need to include when creating lists of elements, and 
the best way to pick a key is to use a string that uniquely identifies a list item among its siblings.

#### What is the purpose of a key?

* **Keys** help **React** identify which items have changed, are added, or are removed. Keys should be given to the elements 
inside the array to give the elements a stable identity.

#### What is the spread operator?

* The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an 
array out into a function’s arguments.

#### List 4 things that the spread operator can do.

1. Copying an array

2. Concatenating or combining arrays

3. Using Math functions

4. Using an array as arguments

#### Give an example of using the spread operator to combine two arrays.

```
const myArray = [`1`,`2`,`3`]
const yourArray = [`4`,`5`,`6`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 1 2 3 4 5 6

```

#### Give an example of using the spread operator to add a new item to an array.

```
const fewFruit = ['A','B','C']
const fewMoreFruit = ['1', '2', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "1", "2", "A", "B", "C" ]

```

#### Give an example of using the spread operator to combine two objects into one.

```

const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂

```

#### In the [video](https://www.youtube.com/watch?v=c05OL7XbwXU&ab_channel=SteveGriffith-Prof3ssorSt3v3), what is the first step that the developer does to pass functions between components?

* create the function where the state will be changed.

#### In your own words, what does the **increment** function do?

* the function will loop through the people array and find the match name and then update the count using the map method.

#### How can you pass a method from a parent component into a child component?

* passed it with a prop to the child component.

#### How does the child component invoke a method that was passed to it from a parent component?

* will invoke it using the state method, by using the button will invoke the state method and pass the data.

## Things I want to know more about

* learn more about the map function

* learn more about state

* learn more about pass functions between components
