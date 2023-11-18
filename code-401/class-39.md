
# Class 39 Reading Notes

## Redux Toolkit (RTK)

1) What concerns are addressed by Redux Toolkit? Redux Toolkit was created to help address these issues:

- "Configuring a Redux store is too complicated"
- "I have to add a lot of packages to get Redux to do anything useful"
- "Redux requires too much boilerplate code"

2) What does configureStore() do? wraps createStore to provide simplified configuration options and good defaults. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.

3) How would I use createSlice()?  accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.
   
## MobX

1) What is MobX? MobX is a simple, scalable state management solution.

2) How does MobX make it “impossible” to produce an inconsistent state? Make sure that everything that can be derived from the application state, will be derived. Automatically.

3) How would we build a reactive user interface? with the observer wrapping components dont need to individually re-render or call state with the useState. Making these components reactive to the changes with the user interface.

## Reflection

1)I would like to be able to understand how to use this and be able to incorporate this in my project. I would like to learn about MobX more and be able to integreat it into projects to make things easier to transfer between components.
