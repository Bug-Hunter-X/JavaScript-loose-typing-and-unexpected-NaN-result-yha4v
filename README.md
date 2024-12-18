# JavaScript Loose Typing Bug

This repository demonstrates a common error in JavaScript related to loose typing and the unexpected result of `NaN` when adding a number and `undefined`.

The `bug.js` file contains the buggy code, showing how providing only one argument to a function expecting two arguments leads to `NaN` being returned.

The `bugSolution.js` file demonstrates a potential fix using strict equality checks (`===`) and default parameters to handle cases with missing arguments.

This example highlights the importance of defensive programming and handling potential `undefined` or `null` values to avoid unexpected behavior in your JavaScript code.  Using TypeScript or a similar language with static typing would help prevent this kind of error.