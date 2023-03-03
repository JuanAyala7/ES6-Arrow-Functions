# ES6-Arrow-Functions
## Why is this important?

A ES6 concept called arrow functions or you might also hear people refer to it as the fat arrow. 

Essentially all that arrow functions are is a shorter way of writing a Javascript function.

## Lessons Learned

With arrow functions, you can take it a step further. It lets us delete the function keyword and replace it with an equals sign followed by a right angle bracket.

With arrow functions, if we have more than one input such as x and a y and we simply multiplied x by y in the body of our function, then in this case we have two input parameters and we’d need a set of parentheses around them. But if you only have one input or one parameter, you can simply get rid of the parentheses as well.

If you have only a single line statement where you're only returning a single expression, you can actually delete the return keyword and delete the curly braces so you end up with inline code. Now your map function is taking each item in the numbers array and multiplying it by itself and then creating a new array.

## Considerations 

Be careful with the syntax because if you add a space in between, then it's no longer a fat arrow. If you put a single line that's also not a fat arrow. It has to be the equals and the right angle bracket combined together.

With the syntax being much shorter, <em>there are pros and cons</em>:

It might be that for a beginner coming to Javascript this would be difficult to understand. Especially in cases where you have people on your team who are more junior, having code like this wouldn’t be ideal. So depending on your project, your use case, your team, your own level of comfort with this kind of shortened syntax, then you can choose to use it but you don't have to. 

Just be aware of that because in React, we use these array functions like map, filter, reduce a lot, and in these cases you will see a lot of people using arrow functions inside just because it makes it simpler and you can achieve things just in one line. But it does take a little bit of getting used to.


### Resource: https://hacks.mozilla.org/2015/06/es6-in-depth-arrow-functions/
