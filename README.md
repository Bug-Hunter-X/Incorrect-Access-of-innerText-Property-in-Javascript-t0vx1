# Uncommon HTML Bug: Incorrect Access of innerText Property

This repository demonstrates a subtle bug related to accessing the `innerText` property of an HTML element using Javascript. The bug arises from incorrectly accessing the element and not using the appropriate DOM manipulation methods.

## Bug Description

The bug occurs in `bug.html`. The Javascript code attempts to access the `innerText` property of a div element using an incorrect approach and not using `document.getElementById()` method. This results in a runtime error.

## Solution

The solution, provided in `bugSolution.html`, correctly accesses the div element using `document.getElementById()` method before accessing its `innerText` property. This ensures that the code functions as intended.

## How to reproduce the bug
1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe the error in the browser's console.

## How to test the solution
1. Open `bugSolution.html` in a web browser.
2. Observe the `innerText` value of the div element in the browser's console. The console should correctly print the text content within the div element.