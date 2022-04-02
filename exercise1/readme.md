# Exercise 1
All of these exercises are using Deno for javasript execution. In this exercise we are doing some very basic programming things.




## Task 1

Make a javascript console program that prints "Hello daddy" to console.

Example output of the program
```
Hello daddy
```

## Task 2

Make a javascript console program that assigns expression value 5 + 5 to variable named value. Variable type should be const. After assigment print value to console.

Example output of the program
```
10
```


## Task 3

Make a javascript console program that assigns value 4 to variable named a and value 5 to variable named b. After this make third variable named c and assign sum of the a and b to that variable. In the end print variable c to console.

All variables should be const type.

Example output of the program
```
9
```

## Task 4

Make a javascript console program that has two variables of any name. First variable contains value "Hello" and second variable contains value "world". After this make third variable named message and concat two strings to that. 

All variables should be const type.

When you print this message variable to console i should show following:
```
Hello world
```



## Task 5

This is first task to contain if statements you can learn more about this from:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else

Make a javascript console program that has two number variables a and b and assign number values to these. After these assigments make if else statement that check if variable a is larger than variable b 
if it is then program should print text "Variable a is larger" and otherwise it should print Variables are either same value or b is larger.


## Task 6

Usually in programming languages remainder is calculated using % character for example:
```js
console.log(12 % 5);
// expected output: 2
```

Make a javascript console program that first assignes number to variable and then if the number
is even prints text "Number is even" and if the number is not even does nothing.

## Task 7

Make a javascript console program that first assignes number to variable and then if the number is smaller than
5 it prints "Its smaller than five" but if the number is smaller than 10 its only printing "Its smaller than 10"
Otherwise the program is printing "Its too big". In the end program prints text "Done".


## Task 8

Make a javascript console program that first assigns some text to variable and then if text in that variable
equals "meat" then you print text "Cat likes meat"

## Task 9

This is first exercise to use for loop you can learn more about this from:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration

Make a javascript program that prints numbers 1 - 10 using for loop.

## Task 10

Make a javascript program that assigns number to variable and then prints word "cow"
as many times that variables value is;

## Task 11

Make a javascript program that counts from 10 to zero and prints the numbers.

## Task 12

Make a javascript program that prints all the variables that are divisible by 2 between
0 - 30 using for loop.

## Task 13

This is first exercise to use while loop you can learn more about while loops from:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/while

Mak a javascript program that assigns number 50 to variable and then using while loop divides 
the variable until its smaller than 1. In the end print the variables value.

## Task 14

This is first exercise to use functions you can learn more about functions from:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions

Example function
```js
function square(number) {
  return number * number;
}
```

Make a javascript function named hello which prints text "Hello cow" and then call this in your program

## Task 15

Make a javascript function named hello which has one parameter named name. When you call this function
it should print to console "Hello ${name parameter value}"

## Task 16

Make a javascript function names calculateRectangleArea that has two parameters width and height. 
This function calculates the area of the rectange and then returns that.

```javascript
console.log(calculateRectangleArea(5, 5))
// Expected output 25
```

## Task 17

This is first exercise to use arrays you can learn more about them from:
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array

Make a javascript program that first assigns three numbers to array and then using loop 
calculates sum of these values.


## Task 18

Make a javascript function that takes number array as a parameter and then calculates
mean of the numbers in the array and returns this mean value. Prove that this function
works correctly.

## Task 19

Add numbers of 1-100 to number array using for loop.

## Task 20

Fifo queue is a structure in which elements are added in and firstly
added element comes and then the second and so on. Use number array
as fifo queue

Hint
```javascript
array = []

// Removes the first element
array.shift()

// Adds new element to the back of the array
array.push(5)
```

## Task 21

This is a first task which uses javascript objects. https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects

In javascript objects can be constructed using following notation:
```javascript
// This creates empty object
const obj = {}

// Object can also be initialized properties
const obj = {
  name: "matti",
  age: 42
}

// Then the properties can be accessed with following
console.log(obj.name) // prints "matti"

const a = obj.name
console.log(a) // prints "matti"

```

Construct object cat which has properties name and breed which have any 
string type value.

## Tasks 22

Tasks can be tought as a blueprint for building something. Methods are functions that belong to the class.

Example class
```javascript

// Here we define the blueprint (class) for the house
class House {
	openDoor() {
    	console.log("Open door")
  	}
}

// Here we make a instance of House class
const firstHouse = new House()

// Here we call openDoor method
firstHouse.openDoor()

```

Make a class named Cat and then implement method called makeSound which should
print something to the console. Then make a instance of the class and call the method.