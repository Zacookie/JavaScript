# Function Expressions

Another way to define a function is to use a *function expression*. To define a function inside an expression, we can use the `function` keyword. In a function expression, the function name is usually omitted. A function with no name is called an *anonymous function*. A function expression is often stored in a variable in order to refer to it.

Consider the following function expression:
![image](https://cdn.discordapp.com/attachments/720883676338061474/722685099572985876/Screen_Shot_2020-06-16_at_6.41.53_PM.png)
To declare a function expression:

1. Declare a variable to make the variable’s name be the name, or identifier, of your function. Since the release of ES6, it is common practice to use `const` as the keyword to declare the variable.

2. Assign as that variable’s value an anonymous function created by using the `function` keyword followed by a set of parentheses with possible parameters. Then a set of curly braces that contain the function body.

To invoke a function expression, write the name of the variable in which the function is stored followed by parentheses enclosing any arguments being passed into the function.
```js
variableName(argument1, argument2)
```
Unlike function declarations, function expressions are not hoisted so they cannot be called before they are defined.

---
> Example Code
```js
const plantNeedsWater = function(day) {
  if (day === 'Wednesday') {
    return true;
  } else {
    return false;
  }
  plantNeedsWater('Tuesday')
}
console.log(plantNeedsWater('Tuesday')); // Prints: false
```