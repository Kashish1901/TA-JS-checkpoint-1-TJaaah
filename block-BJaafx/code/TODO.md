1. Using loops take 10 inputs from user and find the average of all the numbers.
   
2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
```js
function getEvenSum(max=10){
  let sum=0;
for (let i =0 ; i % 2 ===0; i++){
sum =sum +i{
     console.log(sum);
    }
  }
}
```
4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
```js
function getOddSum(max=10){
  let sum=0;
for (let i =0 ; i % 2 != 0; i++){
sum =sum +i{
     console.log(sum);
    }
  }
}
```
5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.
```js
function  getProductOfDigits(num){
  if (num < 0 ){
    return `not a valid input`;
  } else{
    return *;
  }
}
- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // 'Bigger than 5' since 10 is more than 5.i.e. (num > 5)
check(1); // 'Smaller than 5' since 1 is less than 5.i.e. (num < 5)
check(5); // 5 , last condition return num.
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // 'You are arya' beacuse getOutput function accepts the naame and if name === arya it should print this mssg
getOutput('John'); //  'You are john'
getOutput(); // 'Who are you' becasue as it accepts name and if no name is provided it should ask for the name.
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // You are arya    who are you
getOutput('John'); // You are john    who are you
getOutput(); // Who are you

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
```js
A function can have multiple return statements but only one of them will be executed because once a return statement is executed, the program control moves back  skipping the remaining statements of the current method.
```
10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
```js
A for loop is a single-line command that will be executed repeatedly. While loops can be single-lined or contain multiple commands for a single condition.We can use for loop when we know the number of repetations and while loop when we don't know number of times it to be exexuted.
for example for loop can we used when we want to return numbers from 1-10 in a sequence and while loop can be used to define a situation to purchase a phone till the bank balance comes out to 0.
```