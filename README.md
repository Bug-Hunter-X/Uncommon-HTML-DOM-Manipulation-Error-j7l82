# Uncommon HTML Error: Incorrect DOM Manipulation

This repository demonstrates a subtle error in HTML DOM manipulation that can cause unexpected behavior or errors. The error involves using `document.querySelector()` to select an element by its ID when `document.getElementById()` is the more appropriate method.

## Bug Description

The bug lies in the JavaScript code within the HTML file.  `document.querySelector("#myDiv")` is used to select an element with the ID "myDiv." While this works, it's less efficient and can be problematic in specific scenarios. Using `document.getElementById()` is the correct and more efficient method for selecting elements by ID.

## Bug Solution

The solution is to replace the incorrect method `document.querySelector` with the correct method `document.getElementById`.  This change ensures the proper selection of the element and prevents potential issues.  Refer to the `bugSolution.html` file for the corrected code.