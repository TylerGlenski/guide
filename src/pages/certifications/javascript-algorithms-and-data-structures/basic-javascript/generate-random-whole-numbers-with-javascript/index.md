---
title: Generate Random Whole Numbers with JavaScript
---
## Generate Random Whole Numbers with JavaScript
When we pass ``` Math.random() ``` as a paramater of ``` Math.floor() ``` the result is rounded down to the nearest whole number. 

</br>

## Hint:
``` Math.floor(Math.random() * 5) ``` would return a random number between 0 and 4.

</br>

## Solution:

```javascript

var randomNumberBetween0and19 = Math.floor(Math.random() * 20);

function randomWholeNum() {

  // Only change code below this line.

  return Math.floor(Math.random() * 10);
}

```
