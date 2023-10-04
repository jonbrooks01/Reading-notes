# Class 29 Reading Notes

## Extracting State Logic into a Reducer

1) Adding a reducer helps reduce the complexity of the code and makes things easier to read.

2) useReduce is used by removing all the setState from the original functions, then you implement the dispatch so you can pass the information to the state which will pass it to the useReduce function which will in turn return the state. (React will return the state)

3) useReduce is very similar to the common list function of 'reduce'. Since the useReduce, reduces the amount of code that is needed in the code base and the state is handled in a different file.

4) Its best to use the useReducer in many circumstances. upfront its more code to write however in the long run it can make code easier to read. useReduce is easier to write tests for since it is a purely a function. also debugging can be simpler to since state doesn't get updated in several locations.

## Reflection

1) I'm interested in how to use this useReduce method in order to make code more readable and usable.
