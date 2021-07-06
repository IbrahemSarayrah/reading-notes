# Concepts of Functional Programming in Javascript

#### What is functional programming?

* Functional programming is a programming paradigm a style of building the structure and elements of computer programs that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

#### What is a pure function and how do we know if something is a pure function?

* Pure functions are stable, consistent, and predictable. Given the same parameters, pure functions will always return the same result

* It returns the same result if given the same arguments

* It does not cause any observable side effects

#### What are the benefits of a pure function?

* The code’s is easier to test.

* We don’t need to mock anything. So we can unit test pure functions with different contexts:

> Given a parameter `A` → expect the function to return value `B`
>
> Given a parameter `C` → expect the function to return value `D`

#### What is immutability?

* When data is immutable, its state cannot change after it’s created, unchanging over time or unable to be changed.

#### What is Referential transparency?

* if a function consistently yields the same result for the same input, it is referentially transparent.

# Node JS

#### What is a module?

* module is a javascript file and will split our code to a logical module there will be different code in every module and will have simple or complex functionality.

#### What does the word ‘require’ do?

* the require function is on the global object in nodeJS and we can use it in other module (other javascript files), with require we can use function in other module.

#### How do we bring another module into the file the we are working in?

* we use the require function and we pass the file path in the require function

#### What do we have to do to make a module available?

* we call a part of module using module.exports = to the part we want
