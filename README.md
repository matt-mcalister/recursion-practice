# Palindrome Syndrome

### Introduction
A palindrome is a word, phrase, or sequence that reads the same backwards and forwards.

### Problem Statement
Write out the function `palindrome()` that takes in a string as an argument and determines whether that string is a palindrome.

### Example

* `palindrome("racecar")` gives a boolean output of **true** because "racecar" is a palindrome.
* `palindrome("brooklyn")` gives a boolean output of **false** because "brooklyn" is not a palindrome.

What would the output for the following strings be?
* `palindrome("noon")`
* `palindrome("five")`
* `palindrome("radar")`
* `palindrome("T. Eliot, top bard, notes putrid tang emanating, is sad; I'd assign it a name: gnat dirt upset on drab pot toilet")`


____________

# Fibonacci Challenge

### Introduction

The Fibonacci Sequence is the series of numbers:
 1, 1, 2, 3, 5, 8, 13, 21, 34, ...
The next number is found by adding up the two numbers before it.
Example: the next number in the sequence above is 21 + 34 = 55

### The Problem Statement

We want to write a function that takes n as an argument and prints
the nth Fibonacci number in the sequence. Think of n being the step in the sequence.

### Example

Here are some example inputs and their expected return values:

If n = 1, output should be 1
If n = 2, output should be 1
If n > 2, output should be sum of the previous two values

```javascript
function fibonacci(n) {
  // ...
}

fibonacci(7)
# => 13
```