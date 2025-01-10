# Incorrect Null Handling in JavaScript Function
This repository demonstrates a common bug in JavaScript: incorrect handling of null values in a function. The `foo` function is intended to add two numbers, but it returns null if either input is null.  A more robust solution would handle null values appropriately, either by returning 0, throwing an error, or using a default value.

## Bug
The bug lies in the `foo` function's handling of null values.  Simply returning null can lead to unexpected behavior in larger programs.  See `bug.js` for the problematic code.