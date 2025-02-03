# TypeScript Type Error: Type 'string' is not assignable to type 'number'

This repository demonstrates a common TypeScript type error and its solution.

## The Bug
The `add` function is defined to accept two numbers and return their sum. However, the code attempts to call it with a string ('10'), leading to a type error.

## The Solution
The solution involves ensuring that the arguments passed to the `add` function are numbers.  This can be done using type guards, explicit type casting or input validation.