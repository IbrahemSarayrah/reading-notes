# Review, Research, and Discussion

## Describe what Array.map() does

* The map() method creates a new array with the results of calling a function for every array element, and this method does not change the original array

* The map() method calls the provided function once for each element in an array, in order.

## Describe what Array.reduce() does

* The reduce() method in JavaScript is used to reduce the array to a single value and executes a provided function for each value of the array (from left-to-right) and the return value of the function is stored in an accumulator.

* reduce() does not execute the function for empty array elements.

* reduce() does not change the original array.

## Provide code snippets showing how to use superagent()

* With normal Promise .then() syntax

> ```
>  let getCharacters = ()=> {
>    superagent.get('https://swapi.dev/api/people')
>    .then(data =>{
>     let results = data.body.results.map(data=>{
>        return {[data.name] : data.url}
>      })
>      console.log(results)
>    }).catch(err => console.error(err))
>  }
>
>  getCharacters();
> ```

* With async / await syntax

> ```
>  let cityInfo = async (cityName)=>{
>
>    let cityData = await superagent.get(`https://geocode.xyz/${cityName}?json=1`)
>
>     let cityInfo = {
>       city : cityData.body.standard.city,
>       latitude: cityData.body.latt,
>       longitude: cityData.body.longt,
>     } 
>          console.log(cityInfo)
>  }
>
>  cityInfo('amman')
> ```

## Explain promises as though you were mentoring a Code 301 level student

* Promises are used to handle asynchronous operations in JavaScript. They are easy to manage when dealing with multiple asynchronous operations where callbacks can create callback hell leading to unmanageable code.

* the asynchronous method returns a promise to supply the value at some point in the future.

* A Promise has four states:

1. **fulfilled:** Action related to the promise succeeded

2. **rejected:** Action related to the promise failed

3. **pending:** Promise is still pending not fulfilled or rejected yet

4. **settled:** Promise has fulfilled or rejected

## Are all callback functions considered to be Asynchronous? Why or Why Not?

* no, not always callback functions considered to be Asynchronous, Every asynchronous function takes a function argument, but not every function that does so is asynchronous.

* For a function to be asynchronous it needs to perform an asynchronous operation. It needs to incorporate the argument callback in handling the results of this asynchronous operation. Only this way the function becomes asynchronous.
