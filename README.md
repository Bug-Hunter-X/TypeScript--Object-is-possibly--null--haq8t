# TypeScript Bug: Object is Possibly 'null'

This repository demonstrates a common TypeScript error: `Object is possibly 'null'.`  The error arises when attempting to access properties of a variable that might be null or undefined without proper null checks.

The `bug.ts` file contains the erroneous code.  The `bugSolution.ts` file provides a corrected version with null checks.

## How to reproduce:

1. Clone this repository.
2. Compile the `bug.ts` file using the TypeScript compiler (tsc).
3. Observe the compiler error.

## Solution:

The solution involves adding null checks to ensure that the variable is not null before accessing its properties.  This is shown in `bugSolution.ts`.