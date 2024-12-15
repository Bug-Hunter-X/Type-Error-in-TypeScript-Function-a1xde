# Type Error in TypeScript Function

This repository demonstrates a common type error in TypeScript. The `add` function is defined to accept two numbers as arguments, but the code attempts to pass a string ('20') as the second argument, resulting in a type error.

## Bug

The bug is in the `bug.ts` file. The `add` function is called with a string argument instead of a number, causing a type error. The TypeScript compiler will report this error, and the code will not compile successfully.

## Solution

The `bugSolution.ts` file provides a corrected version of the code.  The solution involves ensuring that only numbers are passed to the `add` function. This can be achieved through input validation or by using type guards to explicitly check the type of each parameter.

## How to reproduce

1. Clone the repository.
2. Navigate to the directory.
3. Compile the code using the TypeScript compiler: `tsc bug.ts`
4. Observe the type error reported by the compiler.  Attempt to run `node bug.js` and observe the runtime error.
5. Compile and run the solution: `tsc bugSolution.ts` and `node bugSolution.js`.  The runtime error will no longer occur. 