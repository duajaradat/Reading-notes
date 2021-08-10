## Lists and Keys

**1-What does .map() return?**
 map can return the element or the index or the array.

**2-If I want to loop through an array and display each value in JSX, how do I do that in React?**
 first use `map()` method , it will return you a new array , then we use this array in `JSX`.

**3-Each list item needs a unique `key`.**

**4-What is the purpose of a key?**

to make the react know which element has changed.

## The Spread Operator

**1- What is the spread operator?**

spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

**2-List 4 things that the spread operator can do.**

1- Copying an array

2- Concatenating or combining arrays

3- Using Math functions

4- Using an array as arguments

5- Adding an item to a list

6- Adding to state in React


7- Combining objects

8- Converting NodeList to an array

**3-Give an example of using the spread operator to combine two arrays.**

        const objectOne = {hello: "🤪"}
        const objectTwo = {world: "🐻"}
        const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
        console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
        const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
        objectFour.laugh() // 😂😂😂😂😂

**4-Give an example of using the spread operator to add a new item to an array.**

        const fewFruit = ['🍏','🍊','🍌']
        const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
        console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]


