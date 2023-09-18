
const array = [{ good }, null, { great }, undefined]
 
const truthyArray = array.filter(Boolean)
// truthyArray = [{ good }, { great }]

The filter(Boolean) step does the following:

1. Each item in the array is passed to the Boolean constructor
2. The Boolean constructor coerces each item to true or false depending on whether it’s truthy or falsy
3. If the item is truthy, we keep it
