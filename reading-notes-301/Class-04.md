# React Docs - Forms

#### What is a ‘Controlled Component’?

* a JavaScript function that handles the submission of the form and has access to the data that the user entered into the
form, and the input form element whose value is controlled by React is called a **controlled component**.

#### Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them?

* we should update the state with their responses as soon as they enter them, thats because every elements maintain their own state and update it based on user input.

#### How do we target what the user is entering if we have an event handler on an input field?

* we can target the input field by adding attribute value for the input field then use `this.setState({value: event.target.value}`

#### Why would we use a ternary operator?

* we use the ternary operator to as a shorthand way for writing an if-else statement thats will make the the if-else statement
more simplify and makes the code easier to read.

#### Rewrite the following statement using a ternary statement

```
  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

```

* ternary operator :

```
x === y ? console.log(true) : console.log(false)

```
