# Functions
When writing javascript code, you might find that you want to execute the same line or lines of code multiple times. Functions are a tool that allows us to write our code once, and then use it as many times as we want in our code.

To create a function we use the function keyword, followed by a name and 2 brackets, which hold any arguments for the function. The code to be executed in the function is wrapped in curly braces.

Let’s take a look at an example function and break it down piece by piece:

```js
function squareNumber(num) {
	return num * num;
}
```

**`function`**: declaring that we are starting a function \
**`squareNumber`**: the name of the function \
**`(num)`**: num is the variable that we are passing to the function, which we need to run the code inside of it
return num * num: This is the line of code we actually want to execute. The return keyword sends the result of the function back to wherever it was called from.

To use a function, you simply call the name of the function, with the value you want to input for the argument in brackets. Expanding on the example above we have the following code:

```js,playground
function squareNumber(num) {
	return num * num;
}

const result = squareNumber(4);
console.log(result); // Outputs 16
console.log(squareNumber(5)); // Outputs 25
```

Functions can be extremely useful to help organize code, and shorten the length of your code by saving yourself from repeating. Functions can also take any number of arguments (including 0), and do not have a limit to the # of lines of code you can put in them.

