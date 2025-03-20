# Review Week 9

## Instructions

### 1. Print Numbers from an Array

Given the array:

```js
let numbers = [1, 2, 3, 4, 5];
```

Write code to print each number to the console.

### 2. Print Length of Each String

Given the array:

```js
let words = ["apple", "banana", "cherry"];
```

Write code to print the length of each string to the console.

### 3. Print Only Even Numbers

Given the array:

```js
let numbers = [1, 2, 3, 4, 5, 6];
```

Write code to print only the even numbers to the console. Remember, a number is even if:

```js
if (number % 2 == 0) {
 // It's even
}
```

### 4. If-statement

Write an if-statement so that:

- when `health` is equal or greater to 10 but smaller than 50, it should print "not terrible"
- when `health` is equal or less than 0, it should print "terrible"
- when `health` is equal or greater to 50, it should print "optimal"

Start like this:
```js
let health = 50;

if ....
```

### 5. What is the Value of the Pizza Variable?

What is the value of the pizza variable after this code runs? Explain your answer.

```js
let pizza = ["c", "r", "u", "s", "t"];
​pizza[0] = "t";
```

### 6. Check If Two Arrays Are Equal in Length

Given the arrays:

```js
let array1 = [1, 2, 3];
let array2 = ["a", "b", "c"];
```

Write code to check if they have the same length. Print `true` if they do, and `false` if they don't.

### 7. What are the Values of Halves and Weeks?

What is the value of the `halves` variable?
What is the value of the `weeks` variable?

```js
let ask = function () {
  return 2;
};
let ​halves = ask();
let ​weeks = ask();
```

### 8. Concatenate an Array of Strings

Given the array:

```js
let strings = ["First", "Second", "Third"];
let finalString = "";
```

Write code to concatenate all the strings into one string `finalString`. Then print `finalString` to the console. Start with:

```js
strings.forEach(function(str) {
  // Your code here
});
console.log(finalString); // Should output "FirstSecondThird"
```

### 9. Boolean Values

What are the values of the variables after this code runs?

- isOld
- isYoung
- isAlive
- isConfusing

```js
let isOld = false;
let isYoung = !isOld;
let isAlive = isYoung || isOld;
let isConfusing = isYoung && isOld;
isOld = true;
```

### 10. DOM

Given this HTML:

```html
<h1 class="underline" id="headline">What is JavaScript?</h1>
<p class="underline">JavaScript is a programming language.</p>
```

Write a line of JavaScript that will put the `<h1>` element into a variable named
`headlineElement`.

## What's the output?

For every one of these little programs, determine the output.

### 11.

```js
let names = ["Onehunga", "CBD"];
​names.push("Grey Lynn");
console.log(names);
```

### 12.

```js
let names = ["Onehunga", "CBD"];
console.log(names[2]);
​names.push("Grey Lynn");
console.log(names[2]);
```

### 13.

```js
let names = ["Onehunga", "CBD"];
let superFun = function (element) {
  ​console.log("Element: " + element);
};
names.forEach(superFun);
```
