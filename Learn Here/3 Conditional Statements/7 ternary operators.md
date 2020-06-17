# Ternary Operator

#### In the spirit of using short-hand syntax, we can use a *ternary operator* to simplify an `if...else` statement.

#### Take a look at the `if...else` statement example:
```js
let isNightTime = true;

if (isNightTime) {
  console.log('Turn on the lights!');
} else {
  console.log('Turn off the lights!');
}
```
#### We can use a *ternary operator* to perform the same functionality:
```js
isNightTime ? console.log('Turn on the lights!') : console.log('Turn off the lights!');
```
#### In the example above:

#### - The condition, `isNightTime`, is provided before the `?`.
#### - Two expressions follow the `?` and are separated by a colon `:`.
#### - If the condition evaluates to `true`, the first expression executes.
#### - If the condition evaluates to `false`, the second expression executes.

#### Like `if...else` statements, ternary operators can be used for conditions which evaluate to `true` or `false`.
---
> Example Code
```js
// if...else statements used
let isLocked = false;

if (isLocked) {
  console.log('You will need a key to open the door.');
} else {
  console.log('You will not need a key to open the door.');
}

let isCorrect = true;

if (isCorrect) {
  console.log('Correct!');
} else {
  console.log('Incorrect!');
}

let favoritePhrase = 'Love That!';

if (favoritePhrase === 'Love That!') {
  console.log('I love that!');
} else {
  console.log("I don't love that!");
}
// ternary operators used
let isLocked = false;

isLocked ? console.log('You will need a key to open the door.') : console.log('You will not need a key to open the door.');

let isCorrect = true;

isCorrect ? console.log('Correct!') : console.log('Incorrect!');

let favoritePhrase = 'Love That!';

favoritePhrase === 'Love That!' ? console.log('I love that!') : console.log("I don't love that!");
```