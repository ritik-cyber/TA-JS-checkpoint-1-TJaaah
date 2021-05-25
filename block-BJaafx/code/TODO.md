1. Using loops take 10 inputs from user and find the average of all the numbers.

```js
// let num1 = +prompt("enter the number");
// let num2 = +prompt("enter the number");
// let num3 = +prompt("enter the number");
// let num4 = +prompt("enter the number");
// let num5 = +prompt("enter the number");
// let num6 = +prompt("enter the number");
// let num7 = +prompt("enter the number");
// let num8 = +prompt("enter the number");
// let num9 = +prompt("enter the number");
// let num10 = +prompt("enter the number");
let sum = 0;
for (let i = 1; i <= 10; i++) {
  let userInput = +prompt("enter the number");
  sum += userInput;
}
let avarage = sum / 10;
console.log(avarage);
```

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println("hi");
  i++;
}
```

<!-- hi prints 3 times -->

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

```js
function getOddSum(max = 10) {
  let sum = 0;
  for (let i = 0; i <= max; i++) {
    if (i % 2 == 0) {
      sum += i;
    }
  }
  return sum;
}
getOddSum();
```

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

```js
function getOddSum(max) {
  let sum = 0;
  for (let i = 0; i <= 10; i++) {
    if (i % 2 !== 0) {
      max = sum + i;
    }
  }
  return sum;
}
```

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

```js
function sum(num) {
  let length = String(num).length; // .length property
  let total = 0;

  for (let i = 0; i < length; i++) {
    let last = num % 10;
    total = total + last;
    num = Math.floor(num / 10);
  }
  return total;
}
```

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return "Bigger than 5";
  }

  if (num < 5) {
    return "Smaller than 5";
  }

  return num;
}

check(10); // output // bigger than 5
check(1); // output // smaller than 5
check(5); // output // 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === "Arya") return "You are arya";
  if (name === "John") return "You are john";
  return "Who are you";
}

getOutput("Arya"); // what will be the output // You are Arya
getOutput("John"); // what will be the output // You are john
getOutput(); // what will be the output // Who are you
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === "Arya") console.log("You are arya");
  if (name === "John") console.log("You are john");
  return "Who are you";
}

getOutput("Arya"); // what will be the output // You are arya
getOutput("John"); // what will be the output // your are jhon
getOutput(); // what will be the output // who are you
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

```js
function check(n) {
  if (n < 10) {
    return `You are small`;
  } else {
    return `You are greater`;
  }
}
check(7);
```

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
<!-- in for loop if we have a more than 1 condition we use for loop or if we have only 1 condition we use while loop -->

   <!-- suppose we find to even number so from 1 to 10 so in this question we use while loop -->

ex:

```js
let i = 1;
while (i < 10) {
  if (i % 2 === 0) {
  }
  i++;
  console.log(i);
}
```
