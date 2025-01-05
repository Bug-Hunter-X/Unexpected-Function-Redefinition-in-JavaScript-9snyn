# Unexpected Function Redefinition in JavaScript

This repository demonstrates a common yet subtle bug in JavaScript related to function redefinition.  The code showcases how redefining a function without careful consideration can lead to unexpected behavior and runtime errors. The `bug.js` file contains the problematic code, while `bugSolution.js` provides a solution and best practices for avoiding this issue.

## How to Reproduce the Bug

1. Clone the repository.
2. Navigate to the root directory.
3. Run `node bug.js` in your terminal.

You'll observe that the output differs from what you might initially expect due to the function redefinition.

## Solution

The `bugSolution.js` file presents a solution by implementing better function management and avoiding accidental redefinitions. This improved version provides clarity and maintainability.