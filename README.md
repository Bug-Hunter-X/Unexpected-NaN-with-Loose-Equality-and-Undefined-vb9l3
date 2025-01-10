# JavaScript Loose Equality Bug

This repository demonstrates a common JavaScript bug related to loose equality (==) comparisons involving `null` and `undefined`.  The loose equality operator does not always behave as expected when comparing these values, which can lead to unexpected results and difficult-to-debug errors.

The `bug.js` file contains the problematic code. The `bugSolution.js` file shows how to fix the issue using strict equality (===).