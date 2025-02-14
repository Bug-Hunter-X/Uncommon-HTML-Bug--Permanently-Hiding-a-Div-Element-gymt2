# Uncommon HTML Bug: Permanently Hiding a Div Element

This repository demonstrates an uncommon bug in HTML where a div element is hidden using JavaScript, but a crucial step to re-display the element is missing, leading to it becoming permanently hidden.

The `bug.html` file contains the buggy code, while `bugSolution.html` provides the corrected version.

## Bug Description
The JavaScript function hides the div element with the id "myDiv" using `style.display = "none";`.  However, there's no mechanism to show the element again, causing a permanent disappearance.

## Solution
The solution involves ensuring the div remains in the DOM and restoring the display property to a value that makes it visible.