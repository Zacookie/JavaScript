# String Concatenation

#### Operators aren’t just for numbers! When a `+` operator is used on two strings, it appends the right string to the left string:
```js
console.log('hi' + 'ya'); // Prints 'hiya'
console.log('wo' + 'ah'); // Prints 'woah'
console.log('I love to ' + 'code.')
// Prints 'I love to code.'
```
#### This process of appending one string to another is called *concatenation*. Notice in the third example we had to make sure to include a space at the end of the first string. The computer will join the strings exactly, so we needed to make sure to include the space we wanted between the two strings.
```js
console.log('front ' + 'space'); 
// Prints 'front space'
console.log('back' + ' space'); 
// Prints 'back space'
console.log('no' + 'space'); 
// Prints 'nospace'
console.log('middle' + ' ' + 'space'); 
// Prints 'middle space'
```
#### Just like with regular math, we can combine, or chain, our operations to get a final result:
```js
console.log('One' + ', ' + 'two' + ', ' + 'three!'); 
// Prints 'One, two, three!'
```
---
> Example Code
```js
console.log('Hello' + 'World'); // Output HelloWorld
console.log('Hello' + ' ' + 'World'); // Output Hello World
```