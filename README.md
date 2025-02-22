# JavaScript Calculator with Unhandled Input and Error Handling

This repository demonstrates a simple JavaScript calculator with two potential issues:

1. **Unhandled Non-Numeric Input:** The calculator doesn't explicitly check if the inputs (`a` and `b`) are numbers.  Passing non-numeric values will lead to unexpected behavior (likely NaN).
2. **Basic Error Handling:** The error handling is rudimentary.  While it catches division by zero, it could provide more context and user-friendly messages.

The `bug.js` file contains the code with these issues.  The `bugSolution.js` file offers a possible solution.

## How to Run

1. Clone this repository.
2. Open `bug.js` or `bugSolution.js` in your preferred JavaScript environment (e.g., Node.js, browser's console).
3. Run the code to see the output and behavior.