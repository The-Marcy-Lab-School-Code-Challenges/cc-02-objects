# Code Challenge: Objects

## Instructions

1. Clone down this assignment to your `code-challenges' directory in VScode.  
2. Code your solution using JavaScript in `index.js`. 
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Code Problems

### **Test your solutions for questions 1 and 2 with the following variable:** 
```javascript
const fellows = "marcy fellows"
```

1. Write a function named `charCount` that takes in a string and returns an object where the keys are letters in the string and the value of each key is a count of how many times the character appears in the string.
    
    ```javascript
    const fellows = "marcy fellows"
    charCount(fellows) // returns { "m": 1, "a": 1, "r": 1, "c": 1, "y": 1, " ": 1, "f": 1, "e": 1, "l": 2, "o": 1, "w": 1, "s": 1 }
    ```
    
2. Write a function named `letterCount` that takes in a string and returns an object where the keys are letters in the string and the value of each key is a count of how many times the character appears in the string, not including empty spaces. 
    
    ```javascript
    letterCount(fellows) // returns { "m": 1, "a": 1, "r": 1, "c": 1, "y": 1, "f": 1, "e": 1, "l": 2, "o": 1, "w": 1, "s": 1 }
    ```
    
### Bonus
3. Write a function named `letterCountRefactor` that has the same input and output as `letterCount` except you cannot use a `for let i` loop. Consider using a [`for in`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...in) or [`for of`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for...of]) loop. 


4. Write a function named `vowelCount` that takes in a string and returns an object where the keys are letters in the given string that are vowels and the value of each vowel key is a count of how many times the character appears in the string.

    ```javascript
    vowelCount(fellows) // returns {"a": 1, "o": 1, "e": 1}
    ```
