# The JavaScript Call Stack

#### What is a call ?

* a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

#### How many ‘calls’ can happen at once?

* the call stack is single, functions execution, is done, one at a time, from top to bottom.

#### What does LIFO mean?

Last In, First Out,that the last function that gets pushed into the stack is the first to be pop out.

#### Draw an example of a call stack and the functions that would need to be invoked to generate that call stack

```
function firstFunction(){
  console.log("Hello from firstFunction");
}

function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}

secondFunction();

```
* output

![output](https://cdn-media-1.freecodecamp.org/images/oEp65Ec9CD4CnL7t0uSPoyzrkA1i1BR-Ij1n)

#### What causes a Stack Overflow

* when there is a recursive function (a function that calls itself) without an exit point.

# JavaScript error messages

#### What is a refrence error?

* when a variable that is not yet declared

> console.log(foo)
>
> Uncaught ReferenceError: foo is not defined

#### What is a syntax error?

* this occurs when something that cannot be parsed in terms of syntax, like when try to parse an invalid object using JSON.parse

#### What is a ‘range error’?

* Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

#### What is a ‘tyep error’?

* this types of errors show up when the types (number, string and so on) when trying to use or access are incompatible,like accessing a property in an undefined type of variable.

#### What is a breakpoint?

* The breakpoint can be achieved by putting a debugger statement in your code in the line you want to break.

* You can also add conditional breakpoints by right-clicking a previous set breakpoint, which will make your program stop at that point only if a condition is met

#### What does the word ‘debugger’ do in your code?

* by putting a debugger statement in the code to identify JavaScript errors and we can use it for example to debug huge cycles for specific values.
