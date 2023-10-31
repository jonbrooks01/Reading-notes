# Class 37 Reading Notes

## Multiple Reducers Example

1)  Why create mutiple reducers. You can use multiple reducers to handle different state objects.

2)  How would you combine multiple reducers, you can combine reducers when calling the reducer as combineReducers so it will trigger each reducer function.

3)  How will you manage state as a an immutable object , you will want to return a new state instead trying to mutate the object.


## Redux Docs: Using Combined Reducers

1) combineReducers is a utility function to simplify the most common use case when writing Redux reducers.

2) Explain how combineReducers assembles the new state tree. combineReducers will call each slice reducer with it s current state and then update each slice as needed. it will call all the reducers that are wrapped within the combineReducer.

3) How would you define initial state in an app using combineReducers. each reducer will have their own state defined and then the imported to the combinereducer file where they will be combined and triggered all together when the combineReducer is called.


## Redux Docs: Combined Reducer Syntax

1) Why will you want to split your reducing functions as your app becomes more complex? You will want to split your reducers in a more complex application due to clarity and readability. having the state all in one file will be hard to export and import properly to the child components.

2) The combineReducer helper function turns an object whose values are different reducing functions into a single reducing function you can pass to combineReducers

3) What is a popular convention when naming reducers. A popular convention is to name reducers after the state slices they manage, so you can use ES6 property shorthand notation: combineReducers({ counter, todos }). This is equivalent to writing combineReducers({ counter: counter, todos: todos }).

## Reflection

1) My learning goals are to be able to understand how to incorporate the combineReducer method into my porject to make things easier to manipulate and code.
