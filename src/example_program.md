# Example Program
Combining variables, math, and functions lets you start building useful programs. The following will calculate both the area and circumference of a circle given a radius:

```js,playground,editable
const pi = 3.14

function calculateCircleArea(radius) {
	return pi * radius * radius
}

function calculateCircleCircumference(radius) {
	return 2 * pi * radius
}

function printDataForCircle(radius) {
	const area = calculateCircleArea(radius)
	const circumference = calculateCircleCircumference(radius)

	console.log("For a circle with radius:")
	console.log(radius)
	console.log("Area:")
	console.log(area)
	console.log("Circumference:")
	console.log(circumference)
	console.log("")
}

printDataForCircle(1)
printDataForCircle(2)
printDataForCircle(10)
```

Notice that because of the use of functions, to calculate the area and circumference of a circle with `radius = 11`, only one more line of code is required:

```js
printDataForCircle(11)
```

Try editing or adding more functionality to this program!
