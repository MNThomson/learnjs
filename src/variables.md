# Variables

In JavaScript, variables are used to store data that we want to re use or change in our program. You can think of a variable as a container or a box, which we can open and look inside whenever we want, or change what's in the box. There are 2 ways to declare a variable in Javascript: the let and const keywords. Variables can be used to hold numbers, strings (text) or boolean values (true/false)

This variable can be changed later on
```js
let var1 = "Hello World"
```

This variable can not be changed later on due to the `const` keyword
```js
const var2 = 3
```

If we want to use these variables later on in our code, we can simply write the variable and it will act as the value stored in it

```js,playground,editable
let userName = "Alice"
const userAge = 20
let isMember = true

console.log(userName) // Outputs: "Alice"
console.log(userAge) // Outputs: 20
console.log(isMember) // Outputs: true

userName = "Bob"
console.log(userName) // Outputs "Bob"

userAge = 30 // not allowed since the variable is a const
             // try changing "userAge" to a "let" variable
```
