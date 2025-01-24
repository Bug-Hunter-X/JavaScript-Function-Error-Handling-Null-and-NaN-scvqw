# JavaScript Function Error Handling Null and NaN
This repository demonstrates a common error in JavaScript when handling null and NaN values in a function.  The original `foo` function only explicitly checks for null, leading to unexpected behavior with NaN.  The solution provides improved error handling to address this issue and offer more robust functionality.

## Bug
The `bug.js` file contains a function that adds two numbers. However, the function does not correctly handle NaN (Not a Number) values. When NaN is passed as an argument, the function returns NaN, which can cause unexpected results in calculations. 

## Solution
The `bugSolution.js` file contains the corrected function.  The improved function explicitly checks for NaN in addition to null and handles them appropriately, returning a default value (0 in this case) or throwing an error as needed.  This enhanced error handling makes the function more robust and prevents unexpected results.