# Class 36 Reading Notes

## Async Actions

1) Why use Redux middleware? We use redux middleWare so we can make calls to an api so our application will be more versatile.

2) Consider the Redux Async Data Flow Diagram. Describe the flow in your own words. The state makes a request to the middleware from the UI/event Handler. The Middleware sends the request to the API and then receives the data, then it gets sent to dispatch were it converts the data for the reducer and then sends the data to the store/state.

3) How are we accommodating async in our Redux app? We are making a new function using the Thunk middleware that will handle the async logic

## Thunk Middleware

1) Why would you need redux-thunk middleware? Thunks are the recommended middleware for basic Redux side effects logic, including complex synchronous logic that needs access to the store, and simple async logic like AJAX requests.

2) Redux Thunk middleware allows you to write action creators that return a function instead of an action.

3) Describe how any return value from the inner thunk function will be made available. THe data will be passed in a single object where you can parse the information and be available for usage.

## Reflection

1)I would like to be able to understand how to use this and be able to incorporate this in my project.
