# Accessing Elements
Each element in an array has a numbered position known as its *index*. We can access individual items using their index, which is similar to referencing an item in a list based on the item’s position.

Arrays in JavaScript are *zero-indexed*, meaning the positions start counting from `0` rather than `1`. Therefore, the first item in an array will be at position `0`. Let’s see how we could access an element in an array:

![image](https://cdn.discordapp.com/attachments/720137467579334716/724085157421776987/Screen_Shot_2020-06-20_at_8.12.54_PM.png)

In the code snippet above:

- `cities` is an array that has three elements.
W- e’re using bracket notation, `[]` with the index after the name of the array to access the element.
- `cities[0]` will access the element at index `0` in the array `cities`. You can think of `cities[0]` as accessing the space in memory that holds the string `'New York'`.

You can also access individual characters in a string using bracket notation and the index. For instance, you can write:
```js
const hello = 'Hello World';
console.log(hello[6]);
// Output: W
```
The console will display `W` since it is the character that is at index `6`.

---
> Example Code
```js
const famousSayings = ['Fortune favors the brave.', 'A joke is a very serious thing.', 'Where there is love there is life.'];

const listItem = famousSayings[0];

console.log(famousSayings[2]);

console.log(famousSayings[3]);
```