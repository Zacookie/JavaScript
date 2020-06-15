#Parameters and Arguments

#### So far, the functions we’ve created execute a task without an input. However, some functions can take inputs and use the inputs to perform a task. When declaring a function, we can specify its *parameters*. Parameters allow functions to accept input(s) and perform a task using the input(s). We use parameters as placeholders for information that will be passed to the function when it is called.
#### Let’s observe how to specify parameters in our function declaration:

![image](https://cdn.discordapp.com/attachments/720137077513125962/722193085198499940/Screen_Shot_2020-06-15_at_2.54.37_PM.png)
#### In the diagram above, `calculateArea()`, computes the area of a rectangle, based on two inputs, `width` and `height`. The parameters are specified between the parenthesis as `width` and `height`, and inside the function body, they act just like regular variables. `width` and `height` act as placeholders for values that will be multiplied together.

#### When calling a function that has parameters, we specify the values in the parentheses that follow the function name. The values that are passed to the function when it is called are called *arguments*. Arguments can be passed to the function as values or variables.

![image](https://cdn.discordapp.com/attachments/720137077513125962/722193089699119303/Screen_Shot_2020-06-15_at_2.57.07_PM.png)
#### In the function call above, the number `10` is passed as the `width` and `6` is passed as `height`. Notice that the order in which arguments are passed and assigned follows the order that the parameters are declared.

![image](https://cdn.discordapp.com/attachments/720137077513125962/722193088445153460/Screen_Shot_2020-06-15_at_2.56.47_PM.png))
#### The variables `rectWidth` and `rectHeight` are initialized with the values for the height and width of a rectangle before being used in the function call.

#### By using parameters, `calculateArea()` can be reused to compute the area of any rectangle! Functions are a powerful tool in computer programming so let’s practice creating and calling functions with parameters.
---
> Example Code
```js
function sayThanks(name) {
  console.log('Thank you for your purchase '+ name + '! We appreciate your business.');
}
sayThanks('Cole');
// Output: 'Thank you for your purchase Cole! We appreciate your business.'
```