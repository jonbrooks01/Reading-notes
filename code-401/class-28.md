# Class 28 Reading Notes

## useEffect Hook

1) The main usage for a useEffect Hook is to stay connected to components that are external to the project.

2) The useEffect code will run when the component has been added to the page, then after the dependencies have changed the cleanup code will run the old prop and states while the setup code runs with the new props and state rendering the new information. when it time to disconnect the cleanup code will run one more time to disconnect.

3) The return value from the useEffect should return a cleanUp function that will disconnect from the system

## Reflection

1) Im interested to learn about the useEffect and how it handles API calls within a component.
