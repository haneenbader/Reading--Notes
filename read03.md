# Lifting State Up
Often, several components need to reflect the same changing data. We recommend lifting the shared state up to their closest common ancestor. Let’s see how this works in action.

 (Links to an external site.)Rendering Multiple Components
You can build collections of elements and include them in JSX using curly braces {}.

Below, we loop through the numbers array using the JavaScript map() function. We return a

element for each item. Finally, we assign the resulting array of elements to listItems:
 

*Example :*

const numbers = [1, 2, 3, 4, 5];
const listItems = numbers.map((number) =>
  <li>{number}</li>
);


# lists and keys :

* What does .map() return?
 list of the results. 

If I want to loop through an array and display each value in JSX, how do I do that in React ?  declaring a new array. Array.map() method returns a new array of the jsx elements.
Each list item needs a unique id 
What is the purpose of a key?
A “key” is a special string attribute you need to include when creating lists of elements.


# The Spread Operator

 
* What is the spread operator?
 It takes in an iterable (e.g an array) and expands it into individual elements.
-
* List 4 things that the spread operator can do.

   Using Math functions.
   Using an array as arguments.
   Adding an item to a list.
  Adding to state in React.