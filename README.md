# Silent Failure in accessing non-existent HTML element

This repository demonstrates a common, yet often overlooked, error in JavaScript when interacting with the DOM. Attempting to access a non-existent element using `document.getElementById` results in a silent failure. The code doesn't throw an error, but it also doesn't perform the intended action.

The `bug.html` file showcases this issue.  The `bugSolution.html` provides the correct way to handle potential errors when accessing elements.