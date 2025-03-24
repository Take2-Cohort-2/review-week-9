## Answer 1

const numbers = [1, 2, 3, 4, 5];

numbers.forEach(function(element) {
  console.log(element);
});

## Answer 2

let words = ["apple", "banana", "cherry"];

words.forEach(function(element) {
  console.log(element.length);
});

## Answer 3

let numbers = [1, 2, 3, 4, 5, 6];

numbers.forEach(function(element) {
  if (element % 2 == 0) {
    console.log(element);
  }
});

## Answer 4

let health = 35;

if (health >= 50) {
  console.log("optimal");
} else if (health <= 0) {
  console.log("terrible");
} else if (health >= 10 && health < 50) {
  console.log("not terrible");
}

## Answer 5

let pizza = ["c", "r", "u", "s", "t"];

pizza[0] = "t";

Answer is ["t", "r", "u", "s", "t"];

## Answer 6

let array1 = [1, 2];
let array2 = ["a", "b", "c"];

if(array1.length == array2.length) {
  console.log("true");
} else {
  console.log("false");
}

// or this way
console.log(array1.length == array2.length);

## Answer 7
let ask = function () {
  return 2;
};

let halves = ask();
let weeks = ask();

// Halves is 2
// Weeks is 2

## Answer 8
let strings = ["First", "Second", "Third"];
let finalString = "";

strings.forEach(function(str) {
  finalString = finalString + str + " ";
});

console.log(finalString); // Should output "FirstSecondThird"

## Answer 9
let isOld = false;
let isYoung = !isOld;
let isAlive = isYoung || isOld;
let isConfusing = isYoung && isOld;
isOld = true;

// isOld = true
// isYoung = true
// isAlive = true
// isConfusing = false

## Answer 10
// <h1 class="underline" id="headline">What is JavaScript?</h1>
// <p class="underline">JavaScript is a programming language.</p>

let headlineElement = document.querySelector('#headline');

## Answer 11

["Onehunga", "CBD", "Grey Lynn"]

## Answer 12
undefined
Grey Lynn

## Answer 13
"Element: Onehunga"
"Element: CBD"