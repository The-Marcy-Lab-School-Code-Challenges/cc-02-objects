# Code Challenge: Objects

## Instructions

1. Clone down this assignment to your `code-challenges' directory.
2. Code your solution using JavaScript in `index.js`.
3. **Be sure to run and test your code thoroughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Code Problems

1. Write a function named `stringLengths` that takes in an array of strings as an input, and returns an object, where the keys are all the strings in the array, and the value of each key represents the length of that string. 
    
    ```jsx
    const instructors = ["Ben", "Motun", "Gonzolo", "Itzel"]
    stringLengths(instructors) // { Ben: 3, Motun: 5, Gonzolo: 7, Itzel: 5 }
    ```
    
2. Write a function named stringCount that takes in an array of strings and returns an object where the keys are the strings from the array and the value of each key is a count of how many times the string appears in the object. If there are duplicate strings the values should reflect that. 
    
    ```jsx
    const words = ["apple", "orange", "peach", "pear", "apple"]
    stringCount(words) // { apple: 2, orange: 1, peach: 1, pear: 1 }
    
    ```
    

### Bonus

1. Write a function named `highestFrequencyString` that takes in an array of strings and returns the string with the highest frequency in the array and how many times it appears.
    
    ```jsx
    const fruits = ["apple", "orange", "apple", "peach", "pear", "apple", "peach"]
    highestFrequencyString(fruits) // "apple appears 3 times in the array."
    ```
