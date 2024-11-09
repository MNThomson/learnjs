# Math
Doing math in javascript is just about as simple as doing math with a pen and paper. The four main operators in javascript are represented as follows

|Operation|Symbol|
|---|---|
|Addition|`+`|
|Subtraction|`-`|
|Multiplication|`*`|
|Division|`/`|

Using the operators is also about as simple as one would imagine it would be

```js,playground
console.log(2 + 2) // This outputs "4"
```

In most cases, when we want to do math in our javascript programs, it will be with a dynamic value that the user inputs, represented by a variable. Applying what we just learned about variables, let's look at some examples using variables to both hold the numbers and store the result

```js,playground
const number1 = 10
const number2 = 4

const sum = number1 + number2
console.log(sum) // Outputs: 14 c

const difference = number1 - number2
console.log(difference) // Outputs: 6

const product = number1 * number2
console.log(product) // Outputs: 40

const quotient = number1 / number2
console.log(quotient) // Outputs: 2.5
```

There are two more operators that are quite common: `++` and `--`. These are shorthand for incrementing or decrementing a variable by 1, which is very useful when doing things like loops (not covered in this lesson)

The lines of code shown in the two examples below are equivalent

```js,playground
let total = 0
total = total + 1
console.log(total) // Outputs 1
```

```js,playground
let total = 0
total++
console.log(total) // Outputs 1
```

The same is true for the decrementation operator

```js,playground
let total = 10
total = total - 1
console.log(total) // Outputs 9
```

```js,playground
let total = 10
total--
console.log(total) // Outputs 9
```

One final thing to note is that all math done using JavaScript follows the standard order of operations, Where math in parentheses/brackets is executed first, then multiplication and division, then addition and subtraction.
