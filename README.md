# JavaScript: Handling Null, Undefined, and Falsy Values

This repository demonstrates a common JavaScript error involving the incorrect handling of null, undefined, and falsy values within a conditional statement. The original code attempts to distinguish between these values; however, it fails to account for cases where a falsy value, such as 0 or false, leads to an incorrect outcome.

The `bug.js` file shows the erroneous code. The `bugSolution.js` file provides a corrected version which uses a more robust approach to handling the values.

## Bug Description:

The initial implementation uses loose equality (==) checks to compare the input variable to null and undefined.  This approach leads to false positives when falsy values are passed as arguments, as these are treated incorrectly.

## Solution:

The corrected version uses strict equality (===) which differentiates between types and values, effectively resolving the issue and providing a more accurate classification of the input.

## How to run the code:

1. Clone the repository.
2. Open the `bug.js` and `bugSolution.js` files in a JavaScript environment (e.g., a browser's console or Node.js).
3. Run the code in each file and compare the output.