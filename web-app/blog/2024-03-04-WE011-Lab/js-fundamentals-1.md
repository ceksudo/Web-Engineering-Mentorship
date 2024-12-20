---
slug: js-fundamentals
title: WE011-Lab-1 || JS Fundamentals
authors: [ceksudo]
tags: [JS-Fundamentals]
---

## Project Initialization
Using the terminal
1. Create a folder called `js-fundamentals` 
```bash
mkdir js-fundamentals
```
2. Change into the folder `js-fundamentals
```bash
cd js-fundamentals
```  

3. Create a three files namely `index.html`, `styles.css` and `index.js` inside `js-fundamentals` folder
```bash
touch index.html
touch styles.css
touch index.js
```
4. Copy the html source code below  into `index.html` file
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Welcome to JS Fundamentals</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="container">
      <h1>Welcome to js fundamentals</h1>
      <p>This is the start of your journey to becoming a developer!</p>
      <p>Open inspect element:</p>
      <ul>
        <li><strong>Mac:</strong> <code>command + option + i</code></li>
        <li><strong>Windows:</strong> <code>control + shift + i</code></li>
      </ul>
      <script src="index.js"></script>
    </div>
  </body>
</html>
```  
5. Copy the css source code below into `styles.css` file
```css
/* styles.css */

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #f9f9f9;
    margin: 0;
    padding: 0;
}

.container {
    max-width: 800px;
    margin: 50px auto;
    padding: 20px;
    background-image: linear-gradient(135deg, #8e2de2 10%, #4a00e0 100%);
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
}

h1 {
    color: #fff;
    text-align: center;
    margin-bottom: 20px;
}

p {
    color: #fff;
    line-height: 1.6;
    margin-bottom: 15px;
}

ul {
    margin-left: 20px;
    padding-left: 20px;
}

li {
    margin-bottom: 10px;
}

code {
    background-color: #f2f2f2;
    padding: 3px 6px;
    border-radius: 4px;
}

/* Colors */
.primary-text {
    color: #fff;
    /* White text */
}

.secondary-text {
    color: #eee;
    /* Light gray text */
}

.accent-color {
    color: #007bff;
    /* Blue */
}

.success-color {
    color: #28a745;
    /* Green */
}

.error-color {
    color: #dc3545;
    /* Red */
}

.warning-color {
    color: #ffc107;
    /* Yellow */
}
```
6. Copy the JS source code below into `index.js` file and replace the `todoTask()` function with appropriate solution for the requirement. 
```js
// Deliverables

// JavaScript Fundamentals and Data Structures

// Requirement Engineering:
// In this requirement, we'll cover JavaScript fundamentals and data structures to help you build a strong foundation.

// Helper function 
function todoTask() {
    console.log("Replace Your Solution Here");
}

// Variables and Data Types
todoTask();

// ? What is a variable and data types?
todoTask();

// ! A variable is a container for storing data values. You can think of variables as little containers for information that live in a computer's memory. Information stored in variables can be updated or changed.
todoTask();

// ? How many data types are there in JavaScript?
todoTask();

// 1. Declare a variable 'age' and assign your age to it.
todoTask();

// 2. Declare a constant 'name' and assign your name to it.
todoTask();

// 3. Declare a variable 'isStudent' and assign a boolean value to it.
todoTask();

// 4. Declare a variable 'score' and assign a numeric value to it.
todoTask();

// 5. Declare an array 'fruits' and add a few different fruit names to it.
todoTask();

// Console Output
todoTask();

// 7. Use 'console.log' to display a welcome message to the console.
todoTask();

// Math Operations
todoTask();

// 8. Perform addition and multiplication operations on two numbers and store the results in variables.

// Strings
todoTask();

// 9. Create a string variable 'greeting'
todoTask();
// 10. Use string interpolation to create a message by combining 'greeting' and 'name'.
todoTask();

// Conditional Statements
todoTask();

// 11. Write an 'if' statement to check if your age is greater than or equal to 18.
todoTask();

// 12. Use 'if-else' to display different messages based on isStudent value.
// a. If isStudent is true, display 'Welcome to Flatiron!'
// b. If isStudent is false, display 'Welcome!'
todoTask();

// Switch Statements
todoTask();

// Use a switch statement to display different messages based on the value of 'score'.
todoTask();

// Ternary Operator
todoTask();

// Use a ternary operator to display different messages based on the value of 'score'.
todoTask();

// Loops
todoTask();

// 13. Use a 'for' loop to print numbers from 1 to 5.
todoTask();

// 14. Use a 'while' loop to print numbers from 1 to 5.
todoTask();

// Arrays
todoTask();

// ? What is an array?
todoTask();

// 15. Declare an array 'colors' with a few color names.
todoTask();

// Loop through the 'colors' array and print each color to the console.
todoTask();

// Loop through the 'colors' array and print the index of each color to the console.
todoTask();

// ! difference between 'for', 'for...of', and 'for...in' loops
todoTask();

// 16. Add a new color to the 'colors' array.
todoTask();

// 17. Access the first and last color in the array.
todoTask();

// access the color at a specific index.
todoTask();

// find the index of a color.
todoTask();

// check if a color exists in the 'colors' array.
todoTask();

// remove the last color from the 'colors' array.
todoTask();

// remove the first color from the 'colors' array.
todoTask();

// Objects
todoTask();

// ? What is an object?
todoTask();

// 18. Declare an object 'book' with properties 'title', 'author', 'year', 'description', and 'rating'.
todoTask();

// 19. Access the 'title' property of the 'book' object.
todoTask();

// 20. Update the 'title' property of the 'book' object.
todoTask();

// 21. Add a new property 'genre' to the 'book' object.
todoTask();

// 22. Remove the 'rating' property from the 'book' object.
todoTask();

// 23. Loop through the 'book' object and print each property to the console.
todoTask();

// Console Output the following: {book title} by {book author} was published in {book year}. {book description}. It has a rating of {book rating}. The genre is {book genre}.
todoTask();
```
7. Open `index.html` file with a web browser