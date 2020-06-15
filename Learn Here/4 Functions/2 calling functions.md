# Calling a Function

#### As we saw in previous exercises, a function declaration binds a function to an identifier.

#### However, a function declaration does not ask the code inside the function body to run, it just declares the existence of the function. The code inside a function body runs, or executes, only when the function is called.

#### To call a function in your code, you type the function name followed by parentheses.
![image](https://cdn.discordapp.com/attachments/720137077513125962/722189169085906954/Screen_Shot_2020-06-14_at_10.15.43_PM.png)
####  This *function call* executes the function body, or all of the statements between the curly braces in the function declaration.
![image](https://cdn.discordapp.com/attachments/720137077513125962/722189172936278016/Screen_Shot_2020-06-14_at_10.15.48_PM.png)
#### We can call the same function as many times as we needed.
---
> Example Code
```js
function sayThanks() {
  console.log('Thank you for your purchase! We appreciate your business.')
}

sayThanks();
// You can call functions as many times as you want.
sayThanks();
sayThanks();
sayThanks();
sayThanks();
sayThanks();
sayThanks();
// Output: 7 'Thank you for your purchase! We appreciate your business.'
```