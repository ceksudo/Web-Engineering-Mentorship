# Data and Variables
THE BASIS OF STORING INFORMATION

## Table of Content
* Data Types
* The Variable
* The Constant
* What's in a Name?
* Evaluating Expressions
* Operators
* Getting User Input

# Data Types

## String
* Words, letters, digits, special characters
* Must be in single or double quotes
    * "Use double quotes"
    * 'Or single quotes!'
* Quotes within quotes (as long as they're not the same kind)
* Can be very short or very long
* Can be empty (but still a string!)

### Example Code
```js
let emptyString = ""; 
let space = " "; 
let zeeOrZed = "z"; 
let farmBoy = "Kojo"; 
let manInBlack = "Dread Pirate Roberts"; 
let memorableQuote = 'Inigo said, "Hello. My name is Inigo Montoya. You killed my father. Prepare to die."'; 
let rottenTomatoesScore = "97"; 
```

## Number
* Integers
    * Positive numbers 
        * 55
    * Negative Numbers
        * -43  
* Real Numbers
    * Floats (floating points)
        * 66.888 (of size 4 byte)
    * Doubles
        * 6.657888899900098 (of size 8 byte) 
* In JavaScript world, they're all the same type!
* NO quotes - otherwise it's a string
* NO commas


### Example Code
```js
let numberOfOutlaws = 3; 
let mostlyDead = 0.985; 
let energyLevelAfterRevival = -86; 
let canPriceBeNegative = -77.66
```

# A Variable
* Stores information
* Can store many different data types or even collections of data
* The word "variable" means "changeable"
* Declared with the keyword `let`
* Value is assigned with `=`
* In older examples of code you might see the keyword `var` used instead - that's outmoded!
* "Declaring" vs "initializing" and "Declare and initialize

## Delaring
```js
let school;
```

## Initializing
```js
school = "University of Ghana;
```

## Delare and Initialize
```js
let age = 90;
```

# A Constant
* Stores information
* Value is protected and cannot be changed
* Declared with the keyword `const`
* Sometimes ALLCAPS is used instead of camelCase.
* Useful in situations where you want to ensure the value is never altered

## Delare and Initialize
```js
const PI = 3.14;
```

# Comment
* They are readable guidelines for programmers which are not overlooked by the compiler or interpreter 
* Single line comment
```js
// This is how we do Single Line Commenting 
```
* Multi line comment
```js    
/*
This is how
we do multi line
commenting
*/
```

# Semicolon (;)
* It's like a full stop in ending instructions.
* Thus it tell  the Javascript interpreter the end of every instructions
```js
let msg = "We go na be alright";
```

# The Importance of Good Variable Naming

* Be descriptive!
* Readability is more important than length.
* Avoid naming things in a way that one
* variable could be confused for another.
* It should be obvious from the name not only `what` it is but what `data type` it is.
* Use camelCase for JavaScript

### Example Code
```js
/** WHAT'S IN A NAME? **/

// These are not great choices for variable names. 
let book = 'The Princess Bride: S. Morgenstern\'s Classic Tale of True Love and High Adventure, The "Good Parts" Version';
let name = "William Goldman";
let type = "Adventure";
let kind = "hardcover";
let books = 10;

// Declare new variables for the values above
// They should be descriptive, specific and obvious about data type
let bookTitle = 'The Princess Bride: S. Morgenstern\'s Classic Tale of True Love and High Adventure, The "Good Parts" Version';
let bookAuthor = "William Goldman";
let bookGenre = "Adventure";
let bookFormat = "hardcover";
let numCopiesAvailable = 10;
```

# Output Stream
Printing on the Console for end Users
* What is an output device ?
* What is a function? Remember from maths: `f(x) = y`, where `x` is input and `y` is output and `f` is the function  
* Use `console.log()` to print the value in the console
```js
console.log("You don't own me")
```

# Evaluating Expressions
What Is an Expression?
* Combines values, variables, operators, and more
* Can be as simple as a variable or it can be complex with multiple operations
* The expression is computed and returns a value, which is often stored in a new variable
* You can use multiple expressions to compute new values "behind the scenes"

# Operators
## Basic Arithmetic
* (+) Addition
* (-) Mubtraction
* (*) Multiplication
* (/) Division


### Example Code
```js
/** EVALUATING EXPRESSIONS WITH OPERATORS **/

/* Arithmetic */

let a = 7;
let b = 2;
// Print the difference between a and b using the arithmetic operator for subtraction
console.log(a - b);

let m = 7

// In this case, create a variable to store the result, then print the variable name
let mToTheFourthPower = m**4
console.log(mToTheFourthPower);
```


## Increment and Decrement
* (++) Increment
    * Pre and Post
* (--) Decrement
    * Pre and Post

### Example Code
```js
/* INCREMENT & DECREMENT */

// Incrementing
let x = 5;

// Print x++, then print x, then print ++x
// Try to guess the values that will result with each console.log()
console.log(x++); // returns existing value, then increments
console.log(x); // new value
console.log(++x); // increments, then returns new value

// Increment x one more time without printing it, then print x on the next line
x++;
console.log(x);

// Decrementing
let y = 19;

// Print y--, then print y, then print y--
// Try to guess the values that will result with each console.log()
console.log(y--); // returns existing value, then decrements
console.log(y); // new value
console.log(--y); // decrements, then returns new value

// Decrement y one more time without printing it, then print y on the next line
y--;
console.log(y);

```

## Exponentiation
* (**) "to the power of"
* (**2) "squared"
* (**3) "cubed"

### Example Code
```js
/* ORDER OF OPERATIONS */

console.log(8 * (2 + 2 ** 2) - 36 / (14 - 2 ** 3));

```

## Modulo
* (%) Modulo
* Produces the remainder after dividing
*   * 34 % 6 = 4
    * (%) is the modulo
    * 6 is the modulus

### Example Code
```js
/* MODULO */

// Print the remainder from 100 with a modulus of 7
// 7 * 14 = 98, so we expect the value to be 2
console.log(100 % 7);

// Print the remainder from 6 with a modulus of 2
// 2 * 3 = 6, so we expect the value to be 0
console.log(6 % 2);
```

## String
* (+) Combine two strings
* "Concatenation"

### Example Code
```js
/* STRING BUILDING */

let titleAfterMawage = "Princess";
let originalName = "Buttercup";

// Print the title and name together
console.log(titleAfterMawage + " " + originalName);

// What happens if you have a mix of strings and numbers? Try it out.
let numberOfShips = 4;
console.log("You write " + numberOfShips + " copies of a letter. I'll send my " + numberOfShips + " fastest ships, one in each direction."); 
```

## Compound Assignment
* (+=) Add and update value
* (-=) Subtract and update value
* (*=) Multiply and update value
* (/=) Divide and update value

### Example Code
```js
/* COMPOUND ASSIGNMENT */

let numberOfBoos = 3;

// After Buttercup asks the Ancient Woman why she is booing her, she booed 5 more times. Increase the value of the variable, then print it.
numberOfBoos += 5;
console.log(numberOfBoos);
```

# Input stream
Interacting with a User in the Console
* What is an Input device ?
* Use the `readline-sync` library (only have to do this once at the top)
* `input.question()` will print your question to the console
* Usually you need to store their response in a variable
* You can then use that variable however you'd like
* Importing library
    * Incase you don't have access to this library yet
```bash
npm install --global yarn
yarn --version
yarn add readline-sync
```

### Example Code
```js
/** GETTING USER INPUT **/

// Import the readline-sync library as the constant input
// Normally this would go at the top of the file
const input = require('readline-sync');

// Print a greeting to the user
console.log("\nWelcome to the Princess Bride Fan Club!");

// Ask the user for a name and store it in a variable
let favoriteCharacter = input.question("\nWho is your favorite character?\n\t");

// Print a response to the user that includes their input
console.log("\n" + favoriteCharacter + "? That's my favorite character too!");

// Ask the user for another name and store it in a variable
let sixFingeredMan = input.question("\nPop quiz! Who is the Six-fingered Man?\n\t");

// Print a response to the user that includes their input
console.log("\nThat's correct! " + sixFingeredMan + " was the man Inigo was looking for to avenge his father's death.");

```
