# JavaScript Null Argument Handling Bug

This repository demonstrates a common bug in JavaScript functions related to handling null arguments.

## Bug Description

The `foo` function is designed to add two numbers. However, it unexpectedly returns `null` if either argument is `null`. This can lead to unexpected behavior in applications.

## Solution

The solution involves explicitly checking for `null` or `undefined` and handling them appropriately.

## How to reproduce

1. Clone this repository.
2. Open `bug.js` and examine the buggy code.
3. Run `bug.js` and observe the unexpected null outputs.
4. Open `bugSolution.js` and examine the corrected code.
5. Run `bugSolution.js` and see the corrected output.