# The While Loop
You’re doing great! We’re going to teach you about a different type of loop: the `while` loop. To start, let’s convert a `for` loop into a `while` loop:
```js
// A for loop that prints 1, 2, and 3
for (let counterOne = 1; counterOne < 4; counterOne++){
  console.log(counterOne);
}

// A while loop that prints 1, 2, and 3
let counterTwo = 1;
while (counterTwo < 4) {
  console.log(counterTwo);
  counterTwo++;
}
```
Let’s break down what’s happening with our `while` loop syntax:

- The `counterTwo` variable is declared before the loop. We can access it inside our `while` loop since it’s in the global scope.
- We start our loop with the keyword `while` followed by our stopping condition, or *test condition*. This will be evaluated before each round of the loop. While the condition evaluates to `true`, the block will continue to run. Once it evaluates to `false` the loop will stop.
- Next, we have our loop’s code block which prints `counterTwo` to the console and increments `counterTwo`.

What would happen if we didn’t increment `counterTwo` inside our block? If we didn’t include this, `counterTwo` would always have its initial value, `1`. That would mean the testing condition `counterTwo < 4` would always evaluate to `true` and our loop would never stop running! This is called an *infinite loop* and it’s something we always want to **avoid**. Infinite loops can take up all of your computer’s processing power potentially freezing your computer.

So you may be wondering when to use a `while` loop! The syntax of a `for` loop is ideal when we know how many times the loop should run, but we don’t always know this in advance. Think of eating like a `while` loop: when you start taking bites, you don’t know the exact number you’ll need to become full. Rather you’ll eat `while` you’re hungry. In situations when we want a loop to execute an undetermined number of times, `while` loops are the best choice.

---
> Example Code
```js
const cards = ['diamond', 'spade', 'heart', 'club'];

let currentCard;

while ( currentCard != 'spade') {
  currentCard = cards[Math.floor(Math.random() * 4)];
	console.log(currentCard);
}
```