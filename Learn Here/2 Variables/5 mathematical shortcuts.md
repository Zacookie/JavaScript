# Mathematical Assignment Operators

Let’s consider how we can use variables and math operators to calculate new values and assign them to a variable. Check out the example below:
```js
let w = 4;
w = w + 1;

console.log(w); // Output: 5
```
In the example above, we created the variable `w` with the number `4` assigned to it. The following line, `w = w + 1`, increases the value of w from `4` to `5`.

Another way we could have reassigned `w` after performing some mathematical operation on it is to use built-in *mathematical assignment operators*. We could re-write the code above to be:
```js
let w = 4;
w += 1;

console.log(w); // Output: 5
```
In the second example, we used the `+=` assignment operator to reassign `w`. We’re performing the mathematical operation of the first operator `+` using the number to the right, then reassigning `w` to the computed value.

We also have access to other mathematical assignment operators: `-=`, `*=`, and `/=` which work in a similar fashion.
```js
let x = 20;
x -= 5; // Can be written as x = x - 5
console.log(x); // Output: 15

let y = 50;
y *= 2; // Can be written as y = y * 2
console.log(y); // Output: 100

let z = 8;
z /= 2; // Can be written as z = z / 2
console.log(z); // Output: 4
```
---
> Example Code
```js
let levelUp = 10;
let powerLevel = 9001;
let multiplyMe = 32;
let quarterMe = 1152;

// Use the mathematical assignments in the space below:
levelUp += 5; // Output "The value of levelUp: 15"
powerLevel -= 100; // Output "The value of powerLevel: 8901"
multiplyMe *= 11; // Output "The value of multiplyMe: 352"
quarterMe /= 4; // Output "The value of quarterMe: 288"

// These console.log() statements below will help you check the values of the variables.
console.log('The value of levelUp:', levelUp); 
console.log('The value of powerLevel:', powerLevel); 
console.log('The value of multiplyMe:', multiplyMe); 
console.log('The value of quarterMe:', quarterMe);
```