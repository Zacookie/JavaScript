# **Comments**

#### Programming is often highly collaborative. In addition, our own code can quickly become difficult to understand when we return to it— sometimes only an hour later! For these reasons, it’s often useful to leave notes in our code for other developers or ourselves.

#### As we write JavaScript, we can write comments in our code that the computer will ignore as our program runs. These comments exist just for human readers.

#### Comments can explain what the code is doing, leave instructions for developers using the code, or add any other useful annotations.

#### There are two types of code comments in JavaScript:

#### 1. A *single line comment* will comment out a single line and is denoted with two forward slashes `//` preceding it.
```js
// Prints 5 to the console
console.log(5);
```

You can also use a single line comment to comment after a line of code:
```js
console.log(5);  // Prints 5 
```
#### 2. A *multi-line comment* will comment out multiple lines and is denoted with `/*` to begin the comment, and `*/` to end the comment.
```js
/*
This is all commented 
console.log(10);
None of this is going to run!
console.log(99);
*/
```
You can also use this syntax to comment something out in the middle of a line of code:
```js
console.log(/*IGNORED!*/ 5);  // Still just prints 5 
```
---
> Example Code
```js
// Opening Line
console.log('It was love at first sight.');
/*
console.log('The first time Yossarian saw the chaplain he fell madly in love with him.');
console.log('Yossarian was in the hospital with a pain in his liver that fell just short of being jaundice.');
console.log('The doctors were puzzled by the fact that it wasn\'t quite jaundice.');
console.log('If it became jaundice they could treat it.');
console.log('If it didn\'t become jaundice and went away they could discharge him.');
console.log('But this just being short of jaundice all the time confused them.');*/
```