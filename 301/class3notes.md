# [Class 3 Reading Notes](https://github.com/snur206/reading-notes/blob/main/301/class3notes.md)

This topic matters because it dives more into React, introducing what spread operator is and how to pass functions between components.


## React Docs - lists and keys

map() returns a new array.

In React, you set a variable to store the array if you want to loop through an array and display each value in JSX. 

Each list item needs a unique Key.

The purpose of key is that it helps react know what items have changed, added, and/or removed.

## The Spread Operator

Spread operator is a quick and useful syntax to add items to arrays, can combine arrays and objects, and spread an array out into the function's arguments.

List 4 things that the spread operator can do:

- Copy array

- Concatenate/Combine arrays

- Using math functions

- Use an array as arguments

Give an example of using the spread operator to combine two arrays:

```
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩
```

Give an example of using the spread operator to add a new item to an array:
```
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
```
Give an example of using the spread operator to combine two objects into one:
```
[...["😋😛😜🤪😝"]] // Array [ "😋😛😜🤪😝" ]
[..."🙂🙃😉😊😇🥰😍🤩!"] // Array(9) [ "🙂", "🙃", "😉", "😊", "😇", "🥰", "😍", "🤩", "!" ]

const hello = {hello: "😋😛😜🤪😝"}
const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}

const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }
```
## How to Pass Functions Between Components

The first step a developer does to pass functions between components is to create a  function (increment).

Increment function adds a count everytime the button is clicked.

You pass a method from a parent component into a child component by using props.

The child component invokes a method that was passed to it from a parent component by using this.props.name.

## Things I want to know more about

Passing functions between components and spread operator.
