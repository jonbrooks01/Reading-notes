# Class 30 Reading Notes

## Choosing the State Structure

1)

- Group related state variable together so its more efficient
- When making state don't have variables that may clash with one another
- Ensure to keep state outside of the components files
- Keep states simple and pass it to components don't have duplicate states
- Keep states at the parent level so they can be updated easily

## Passing the five principles for structuring state

1) contexts aims to solve the pass down of variable and your able to send it to the child that you want it to go

2) One technique to try before using useContext is passing props

3) You can use useContext with useReducer for complex applications
