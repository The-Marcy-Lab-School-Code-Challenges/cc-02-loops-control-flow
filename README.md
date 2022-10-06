# Code Challenge: Loops with Control Flow

## Instructions

1. Clone down this assignment to your `code-challenges' directory in AWS Cloud9.  
2. Code your solution using JavaScript in `index.js`. 
3. **Be sure to run and test your code throughly!**
4. By the end of Code Challenge, **commit and push your changes up to Github**.
5. Using the browser, verify that your solution is in your remote repo on Github.

## Code Problems

1. Write a function `absoluteValue` that **returns** the absolute value of a number. If the value is not a number, it returns `null`. Complete this function **without** using Math.abs() .
```
absoluteValue(10.35)    //returns 10.35
absoluteValue("hello")  //returns null
absoluteValue(-3)       //returns 3
```

2. Write a function `multiplesOfSixAndNine` that **console logs** all positive numbers from 1 to 100, if a number is a multiple of 6 and a mutliple of 9.
```
multiplesOfSixAndNine() 
// 18
// 36
// 54
// 72
```

### Bonus 
3. Write a function `multiplesOfFourAndSix` that **returns an array** of all positive numbers from 1 to 100 if that number is a multiple of 4 and a mutliple of 6. 
```
multiplesOfFourAndSix() // returns [12, 24, 36, 48,60, 72, 84, 96]
```

4. Write a fucntion named `countMultiplesOfTwo` that takes in an array of integers and returns the number of integers in the array that are multiples of two. 
```
countMultiplesOfTwo([1,2,3,4,5,6,7,8,9,10]) // returns 5
countMultiplesOfTwo([15,23,35,45,67]) // returns 0
countMultiplesOfTwo([2,6,14]) // returns 3
```
