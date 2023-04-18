1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
The difference between the two is that first will return ececution to the caller whereas console.log will log the result in console and is similar to print.

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.
first = sum(10,20);

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
//36 as it will ignore the third value, because it can only accept 2 values i.e. a and b .
4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
```js
function sayHello(name){
  return `Hello ${name}`;
}
6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
//Hello, John

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // "John"

showMessage(); //" Hello John"

alert(userName); // "John"
```

8. What is a Anonymous Function give example of three functions.
An anonymous function is that type of function that has no name or we can say which is without any name.
example:
const addNumbers = function(numA + numb){
  return numA + numB;
}
function() {  
    console.log('Hello');  
}
function(){
  return typeof;
} 
9. Can function declaration be a Anonymous Function? Explain
no  function declaration cannot be a Anonymous Function because the main difference is function name and can't be omited in function decalration but is omited in function declaration.
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
//getSquare
//calcDogAge
//createMultiplesOfN
//checkEven
//addTwoNumbers