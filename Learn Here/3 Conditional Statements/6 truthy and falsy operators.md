# Truthy and Falsy Assignment

Truthy and falsy evaluations open a world of short-hand possibilities!

Say you have a website and want to take a user’s username to make a personalized greeting. Sometimes, the user does not have an account, making the `username` variable falsy. The code below checks if `username` is defined and assigns a default string if it is not:
```js
let defaultName;
if (username) {
  defaultName = username;
} else {
  defaultName = 'Stranger';
}
```
If you combine your knowledge of logical operators you can use a short-hand for the code above. In a boolean condition, JavaScript assigns the truthy value to a variable if you use the `||` operator in your assignment:
```
let defaultName = username || 'Stranger';
```
Because `||` or statements check the left-hand condition first, the variable `defaultName` will be assigned the actual value of `username` if is truthy, and it will be assigned the value of `'Stranger'` if `username` is falsy. This concept is also referred to as *short-circuit evaluation*.
---
> Example Code
```js
let tool = '';
tool = 'marker';

let writingUtensil = tool || 'pen';

console.log(`The ${writingUtensil} is mightier than the sword.`);
```