# Blocks and Scope

#### Before we talk more about scope, we first need to talk about blocks.

#### We’ve seen blocks used before in functions and if statements. A block is the code found inside a set of curly braces {}. Blocks help us group one or more statements together and serve as an important structural marker for our code.

#### A block of code could be a function, like this:
```js
const logSkyColor = () => {
  let color = 'blue'; 
  console.log(color); // blue 
};
```
#### Notice that the function body is actually a block of code.

#### Observe the block in an if statement:
```js
if (dusk) {
  let color = 'pink';
  console.log(color); // pink
};
```
#### In the next few exercises, we’ll see how blocks define the scope of variables.
---
> Example Code
```js
const city = 'New York City';

const logCitySkyline = () => {
  let skyscraper = 'Empire State Building';
  return 'The stars over the ' + skyscraper + ' in ' + city;
};

console.log(logCitySkyline());
```