1. Using loops take 10 inputs from user and find the average of all the numbers.

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
``` 
// undefined variable println so there is an error

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.


function getEvenSum (max){
   if (i % 2 === 0)
   return sum;
}

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

function getOddSum (max) {

}

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

function getProductOfDigits (num){
  if (num < 0)
  return `not a valid input`;
} 

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

check(10); // output Bigger than 5 ; function check the if value and 10 is num so bigger than 5
check(1); // output smaller than 5 ;  function runs first statement then second and it is true so smaller
check(5); // output // 5; does not need to run the if or return as value is 5 already equal 
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // what will be the output// You are arya first if statement is true
getOutput('John'); // what will be the output// You are John second if stateent is true
getOutput(); // what will be the output// Who are you because if statement is false
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // what will be the output // 'Who are you' ; console.log is not an output 
getOutput('John'); // what will be the output // 'Who are you' ; console.log is not an output 
getOutput(); // what will be the output // 'Who are you'; console.log is not an output 
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

Yes

function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

this works because the function will keep running until there is a true value 


10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.


while — loops through a block of code once; then the condition is evaluated. If the condition is true, the statement is repeated as long as the specified condition is true. 
for — loops through a block of code until the counter reaches a specified number.

Use a for loop when you know the loop should execute n times. 
Use a while loop for reading a file into a variable, asking for user input or when the increment value is nonstandard.