# Hidden Div Bug
This repository demonstrates a common yet easily overlooked error in HTML and JavaScript:  hiding a div element without providing a way to make it visible again. The bug is caused by using Javascript to hide the element.  A simple solution involves adding a condition in the javascript to make the element visible again.  The solution file shows how to fix this issue.

## Bug Description
The bug occurs in the `bug.html` file.  When you click the button, the div with the id "myDiv" is hidden using JavaScript. However, there's no mechanism to subsequently display the div. 

## Solution
The solution is provided in `solution.html`. By implementing a condition to check whether the div is hidden or not it can be made to reappear.