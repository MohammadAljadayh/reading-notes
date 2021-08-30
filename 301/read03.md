
# Passing Functions as Props

### What does .map() return?
return new array with the same length of the original array with diffrent in values so the The map() method creates a new array populated with the results of calling a provided function on every element in the calling array.
### If I want to loop through an array and display each value in JSX, how do I do that in React?
-  loop through the numbers array using the JavaScript map() function.
-   return a li element for each item.
-  Finally, we assign the resulting array of elements to listItems.

### Each list item needs a unique **key**.

### What is the purpose of a key?
To get the keys of a Map object, you use the keys() method. The keys() returns a new iterator object that contains the keys of elements in the map.
Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity
Keys used within arrays should be unique among their siblings. However, they donâ€™t need to be globally unique. We can use the same keys when we produce two different arrays

![](https://i.morioh.com/200626/ec9a9e94.jpg)

### What is the spread operator?
The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.   

“Spread operator to the rescue! It looks similar to rest parameters, also using ..., but does quite the opposite.” — JavaScript.info    

### List 4 things that the spread operator can do.
-  Copying an array.
-  Concatenating or combining arrays.
-  Using Math functions.
-  Using an array as arguments.


### Give an example of using the spread operator to combine two arrays.
Using the … spread operator is a convenient way to copy an array or combine arrays, and it can even add new items:


- const fruits = ['🍏','🍊','🍌','🍉','🍍']
- const moreFruits = [...fruits];
- console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
- fruits[0] = '🍑'
- console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍 

### Give an example of using the spread operator to add a new item to an array.
- const fewFruit = ['🍏','🍊','🍌']
- const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
- console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ] 

### Give an example of using the spread operator to combine two objects into one.
The spread syntax is useful for combining the properties and methods on objects into a new object:

- const objectOne = {hello: "🤪"}
- const objectTwo = {world: "🐻"}
- const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
- console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
- const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
- objectFour.laugh() // 😂😂😂😂😂 

## for More Details : 
[The Spread Operator](https://reactjs.org/docs/lists-and-keys.html)

[How to Pass Functions Between Components](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

[React Tutorial through â€˜Declaring a Winnerâ€™](https://reactjs.org/tutorial/tutorial.html)

[React Docs - Lifting State Up](https://reactjs.org/tutorial/tutorial.html)
