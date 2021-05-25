1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}
// its retun the a+b

// second
function sum(a, b) {
  console.log(a + b);
}
//  its console the (a+b)
```

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

<!-- return value of first is (when we give a argument in number so its add and return the value)  -->
<!-- retun value of second number is undefined -->

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

<!-- its dose't change its add the only 2 argument  -->

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

```js
let add = function sum(a, b) {
  return a + b;
};
sum(12, 12);
```

<!-- No we can't store a function in a another variable because the function name is same in variable  -->

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

```js
function sayHello(name) {
  return `Hello ${name}`;
}
sayHello("Arya");
```

6. What will be the output of the function below and why?

```js
let userName = "John";

function showMessage() {
  let message = "Hello, " + userName;
  return message;
}

showMessage();
```

<!-- The output of message is hello,jhoh because username find the value in funcition if it not find then it goes to outside the function e -->

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = "John";

function showMessage() {
  let message = "Hello, " + userName;
  return message;
}

alert(userName); // Output 1 // john

showMessage(); // Output 2 // Hello,john

alert(userName); // Output 3 // john
```

8. What is a Anonymous Function give example of three functions.

```js
let sum = function (a, b) {
  return a + b;
};

let mul = function (a, b) {
  return a * b;
};

let sub = function (a, b) {
  return a - b;
};
```

9. Can function declaration be a Anonymous Function? Explain

<!-- Yes declaration function is be a Anonymous function -->

```js
function sum(a, b) {
  return a + b;
}

let sum = function (a, b) {
  return a + b;
};
```

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```

```js
"find..." - find something
"temp..." - temperature
"lost.."  - lost something
```
