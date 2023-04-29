# Class 05 Reading Notes

## React Docs - Thinking in React

1) The single responsibility principle is when a component should only be doing one thing. If a component grows and does multiple things then it should be broken up into smaller components.

2) To build a static version of the website means to build an app that renders the data model, building components that pass down props without including state at all.

3) Once you've built the static app then you'll start introducing state into the components making it interactive.

4) The three question that can be asked to determine if something requires a state are;

- Does it remain unchanged over time? If so, it isn’t state.

- Is it passed in from a parent via props? If so, it isn’t state.

- Can you compute it based on existing state or props in your component? If so, it definitely isn’t state!

5) Identifying where state should live can be completed with these steps;

- Often, you can put the state directly into their common parent.

- You can also put the state into some component above their common parent.

- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common parent component.

## Higher-Order Functions

1) High-order functions are functions that operate on other functions by either taking them as arguments or by returning them.

2) Line 2 is creating a new variable called 'm' and then comparing that variable to 'n'

3) Using map and reduce in a high-order function, applies to the entire function and all of its elements, building a new array from the returned values. reduce operates the same way.
