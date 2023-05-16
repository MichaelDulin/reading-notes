# Class 4.32 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 32**
- [Scaling Up with Reducer and Context](https://react.dev/learn/scaling-up-with-reducer-and-context)


**Scaling Up with Reducer and Context**
1. How do useReducer and useContext work together to simplify state management in a React application? (At least two paragraphs of prose.)
  - useReducer is a hook that allows you to manage complex state logic by dispatching actions to update the state. It takes a reducer function and an initial state as arguments and returns the current state and a dispatch function. The reducer function specifies how the state should be updated on the dispatched action. With useContext, another hook, we can access the value of a React context. A context provides a way to pass data through the component tree without having to pass props manually at every level. To simplify state managment, you can use useReducer to manage the state/discpatch actions and useContext to provide the state and dispatch functions to all the components that need access to them.

## Things I want to know more about
