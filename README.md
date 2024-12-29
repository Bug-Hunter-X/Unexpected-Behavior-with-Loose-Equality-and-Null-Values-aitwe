# JavaScript Null Value Handling

This repository demonstrates a common JavaScript error related to null value handling and provides a solution.

## The Bug

The `foo` function uses loose equality (`==`) which can lead to unexpected results when comparing with `null` or `undefined`.  This often leads to bugs that are difficult to track down.

## The Solution

The solution uses strict equality (`===`) for better type checking or explicitly checks for null values and handles them appropriately.

## How to Reproduce

1. Clone this repository.
2. Run the `bug.js` script using Node.js or a similar JavaScript environment.
3. Observe the unexpected results.
4. Run the `bugSolution.js` script and compare the results.