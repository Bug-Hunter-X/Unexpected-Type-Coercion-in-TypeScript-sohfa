# Unexpected Type Coercion in TypeScript

This repository demonstrates a common pitfall in TypeScript: unexpected type coercion.  TypeScript's flexibility, while beneficial, can sometimes lead to runtime errors if not handled carefully.

The `bug.ts` file shows a function that is intended to add two numbers, but due to TypeScript's type coercion, it silently concatenates a number and a string.

The `bugSolution.ts` file presents a solution to prevent this problem using type guards or stricter type checking.