# What is a script and functions

### Expression

Evaluates into a sigle value.

Two types:
- just assigns a value to a variable `var color = 'beige'`
- uses two or more values to return single value `var area = 3 * 2`

### Operators

Types: 
- assignment operators - assign a value to a variable  - `var color = 'beige'`
- arithmetic operators - perform basic math - `area = 3 * 2`
- string operators - combine two strings - `greeting = "Hi " "Molly"
- comparison operators - compare two values and return true or false `buy = 3 > 5` (This is false)
- local operators - combine expressions and return true or false - `buy = (5 > 3) && (2<4)`;

Arithmetic operations: 
`+` addition
 `-` substracting 
 `/` division
  `*` mustiplication
`++` increment - adds one from current number
`--` - decrement - substract opne from the current number
`%` - modulus

#### Concatenation

Joining (adding) two strings


## What is a function?

Function let a group of a series of statements toghether to perform a specific task. 

- name your function (name describing the tast the function performs) **calling** the function
- parameters - pieces of information passed to the function 
- return value - response of a function

#### Declaring a function

```
function sayHello() {
  document.write(Hello');
}
```

#### Calling a function

Executing the all the statements between curly braces with a just one line of code

```
sayHello();
```

#### Declaring the function that need information

When declaring a function you give it **paramenters**

```
function getArea(width, height) {
  return width * height;
}
```

Calling the function that need information:

Provided values are called arguments.

Arguments as values:
```
getArea(3, 5);
```

Arguments as variables:
```
wallWidth = 3
wallHeight = 5

getArea(wallWidth, wallHeight);
```

```
function calculateArea(width, height) {
  var area = width * height
  return area;
}
var wallOne = calculateArea(3, 5);
var wallTwo = calculation (8, 5);
```
