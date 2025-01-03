# JavaScript Loose Equality and Null Comparisons

This repository demonstrates a common JavaScript bug related to loose equality (`==`) and null comparisons.

## The Bug
The `bug.js` file contains a function `foo` that adds two numbers. However, it uses loose equality (`==`) to check for null values which can lead to unexpected results.

## The Solution
The `bugSolution.js` file demonstrates how using strict equality (`===`) prevents this issue by correctly identifying null values and handling them appropriately.