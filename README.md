# JavaScript Null and Undefined Handling

This repository demonstrates a common issue in JavaScript related to handling `null` and `undefined` values using loose comparison. The `bug.js` file shows a function that performs addition but does not explicitly handle `null` inputs, potentially leading to unexpected results or errors. The `bugSolution.js` file provides a corrected version that addresses this by explicitly checking for `null` values.

## Bug Description
In JavaScript, loose comparison (`==`) can lead to unexpected behavior. This is especially true when dealing with `null` and `undefined`.  The original code uses loose comparison and does not correctly handle cases where either input is `null`, resulting in incorrect output.  The provided solution uses strict equality (`===`) to explicitly check for null, providing more predictable behavior.

## Solution
The solution utilizes strict equality (`===`) to explicitly check for `null` values before performing the addition. This approach ensures that the function handles `null` inputs correctly, preventing unexpected errors or results.