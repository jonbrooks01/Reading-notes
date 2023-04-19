# Class 02 Reading Notes

## React Lifecycle

1) According to the Diagram the render happened first. 

2) Mounting is the first thing that happens in the life cycle of React

3) In this order;

- Constructor
- render
- React Updates
- ComponentDidMount
- ComponentWillUnmount

4) ComponentDidMount runs the instance of that component in the DOM

## React State Vs Props

1) You can pass arguments into props. props are used to render what you want from that function. you can also use props to display items to the user like titles.

2) States are within the component where as props are passed into the component. states can be updated within the component wheras props need to be updated outside the component. when states are changed it automatically re-renders that component but for props will need to be passed down again.

3) you need to re-render the application when there is a user interface that changed the information thats in state. Props dont change within the component so they dont need to re-render.

4) a user count is something that state would be good for as well as a form where the user has inputted information.