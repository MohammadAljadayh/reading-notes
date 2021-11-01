# Readings: Node Ecosystem, TDD, CI/CD

# Review, Research, and Discussion

## Describe (in plain English) what Array.map() does

- Array.map()

> The map() method creates a new array with the results of calling a function for every array element. The map() method calls the provided function once for each element in an array. 

> Note:map() does not execute the function for empty elements && this method does not change the original array.



## Describe (in plain English) what Array.reduce() does

- Array.reduce() 

> The reduce() method executes a reducer function for each value of an array. reduce() returns a single value which is the function's accumulated result. 

> Note:map() does not execute the function for empty elements && this method does not change the original array.


## Provide code snippets showing how to use superagent() to fetch data from a URL and log the result

- With normal Promise .then() syntax

```
function getCharacters(){
superagent.get(`https://swapi.dev/api/people/?format=json`)
  .then( data => {
  let result=data.body.results.map(char=>{
let name=char.name;
let url=char.url;
return{[name]:url}
  });
  console.log(result);
  })
  .catch(err => console.error(err));
}

 getCharacters();

``` 
- Again with async / await syntax


```
async function getStuff(cityName) {
  let results = await superagent.get(`https://geocode.xyz/${cityName}?json=1`);

 let longt=results.body.longt;
  let latt=results.body.latt;
 let allLocationInfo=[cityName,longt,latt];
    console.log(allLocationInfo);
}

getStuff('Seattle');
getStuff('Amman');
getStuff('Dubai');

```

## Explain promises as though you were mentoring a Code 301 level student

> A promise is an object that may produce a single value some time in the future so A promise like  is an object that encapsulates the result of an asynchronous operation.



## Are all callback functions considered to be Asynchronous? Why or Why Not?

> Well, basically yes, Every asynchronous function takes a function argument, but not every function that does so is asynchronous. It matters how the argument is used inside the function.

> Simply taking a callback doesn't make a function asynchronous. There are many examples of functions that take a function argument but are not asynchronous. For example there's forEach in Array. It iterates over each item and calls the function once per item. 