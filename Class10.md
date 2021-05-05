# JavaScript Error Handling And Debugging

#### order of execution 

* To find the source of an error we need to know the order in which statements are executed some tasks
cannot complete until another statement or function has been run

#### execution contexts

* Every statement in a script lives in one of three execution contexts

> 1. **GLOBAL CONTEXT** Code that is in the script, but not in a function. There is only one global context in any page. 
>
> 2. **FUNCTION CONTEXT** Code that is being run within a function.
>
> 3. **EVAL CONTEXT Text** is executed like code in an internal function called eval

#### Each time a script enters a new execution context there are two phases :

> 1. **PREPARE** 
> 2. **EXECUTE**

#### Error objects :  can help to find where are the mistakes and browsers have tools to help you read them

* When an Er ror object is created, it will contain the following properties

| PROPERTY      | DESCRIPTION |
| ----------- | ----------- |
| name        |Type of execution |
| message   | Description       |
| file Number   | Name of the JavaScript file    |
| line neNumber    | Line number of error       |

* There are seven types of built-in error objects in JavaScript 

| PROPERTY      | DESCRIPTION |
| ----------- | ----------- |
| Error        |Generic error - the other errorsare all based upon this error |
| Syntax Error  |Syntax has not been followed |
| Ref erenceError   |Tried to reference a variable that isnot declared/within scope   |
| TypeError  |An unexpected data type thatcannot be coerced |
| Range Error   |Numbers not in acceptable range  |
|URI Error       |encodeURI ().decodeURI(),and similar methods used incorrectly |
|EvalError        |eval () function used incorrectly |

#### Deal with Error 

* track down the source of the error and fix it there are  developer tools available in browser can help to to track down the error

* The JavaScript console will help u when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be

* The JavaScript console is just one of several developer tools that are found in all modern browsers

* The console will show when there is an error in JavaScript

### Summary 

* Debugging is the process of finding errors. It involves a process of deduction

* The console helps narrow down the area in which the error is located

* JavaScript has 7 different types of errors Each creates its own error object, which can tell you its line number
and gives a description of the error
