# Uncommon HTML Bug: Typo in getElementById

This repository demonstrates a subtle but common error in JavaScript when working with the Document Object Model (DOM) in HTML. The bug arises from a simple typo in the `getElementById` method.

## Bug Description
The bug is caused by a typo in the `getElementById` function. The code attempts to use `getElementByIdx` instead of the correct `getElementById` method. This results in the text within the div not being updated. 

## Solution
The solution involves correcting the typo in the JavaScript code.  Using the correct `getElementById` method allows the code to function as intended, correctly changing the content of the div element.
