
# Passing Functions as Props



![](https://miro.medium.com/max/2000/1*24ayqOY008AvW_VmkqsYdA.png) 

- What does .map() return?  
a list of items (Array);
- If I want to loop through an array and display each value in JSX, how do I do that in React?  
use map method and wrap each value with a jsx tag.
- Each list item needs a unique key.
- What is the purpose of a key?  
they help react identify which values has been changed add or removed. 

## The Spread Operator

* What is the spread operator?
    - In JavaScript, spread syntax refers to the use of an ellipsis of three dots (â€¦) to expand an iterable object into the list of arguments.
* List 4 things that the spread operator can do.
    - Copying an array
    - Concatenating or combining arrays
    - Using Math functions
    - Using an array as arguments
* Give an example of using the spread operator to combine two arrays.
    > const myArray = [`ðŸ¤ª`,`ðŸ»`,`ðŸŽŒ`]

    > const yourArray = [`ðŸ™‚`,`ðŸ¤—`,`ðŸ¤©`]

    > const ourArray = [...myArray,...yourArray]

    > console.log(...ourArray) // ðŸ¤ª ðŸ» ðŸŽŒ ðŸ™‚ ðŸ¤— ðŸ¤©


source](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

## How to Pass Functions Between Components
[![IMAGE_ALT](https://img.youtube.com/vi/c05OL7XbwXU/0.jpg/default.jpg)](https://www.youtube.com/watch?v=c05OL7XbwXU)
* In the video, what is the first step that the developer does to pass functions between components?
* In your own words, what does the increment function do?
