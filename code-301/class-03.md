# Class 03 Reading Notes

## React Docs - Lists and Keys

1) .map() returns a new array.

2) By using curly braces and .map you can loop through the array and display each value in JSX. You would use the curly braces for the new array to display the entire array

3) every list item needs to have a key

4) keys are helpful to identify which items have been changed, add or removed. They provide a stable identity to elements inside an array.

## The Spread Operator

1) The spread operator is a useful and quick syntax for adding items to arrays combining arrays or objects and spreading arrays out to a functions argument.

2) The spread operator can be used for math functions, copying an array, using an array as arguments and adding a state to react.

3) By using the spread operator '...' you can add two arrays together, for example 'const likes = [😃,😁] , const dislikes = [...likes] console.log(dislikes) = [😃,😁]'

4) by introducing a new array and passing in new items plus ...(old array) you can add the new items to the old array; 'const hello = ['hi'] const bye = ['bye',...hello] console.log(bye) = 'bye','hi'.

5) and an object together is similar to adding items to a new array. create a new object then pass the other objects using '{}' and then you can add new items into object using the same process.

## How to Pass Functions Between Components

1) Creates a new function called 'increment'

2) The function 'increment' calls the previous array in people and creates a new array using .map, then the function checks to see if there is a name that matches if there is the name that matches then gets incremented by one.

3) since there within the same componet all thats needed is to create a new variable and then pass it in with 'this'

4) A child component can invoke a method that was passed to it from a parent component by using the 'this.props.whatever' to call and utilize it.
