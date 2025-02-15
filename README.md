# Type 'string[]' is not assignable to type 'string'
This example demonstrates a common type error in TypeScript where an array of strings is passed to a function expecting a single string.

## Bug
The `greeter` function expects a single string argument, but the `user` variable is an array of strings. This leads to a type error.

## Solution
The solution is to either modify the `greeter` function to accept an array of strings or modify how the user variable is handled to only pass a single string to the function.  One solution below shows modifying the greeter function and using the join method to concatenate the array elements.