# Class 4.36 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 36**
- [Dan Abramov Redux Tutorials](https://egghead.io/courses/getting-started-with-redux)
- [worlds easiest guide to redux](https://medium.freecodecamp.org/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)
- [testing reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)
- [Redux Docs](https://redux.js.org/)

****

**Dan Abramov Redux Tutorials**
1. What is the first principle of Redux?
  - The first principle of Reduc is known as "Single Source of Truth" and is a core concept which underlies the Redux state management pattern. The principle states that the entire state of an application should be stored ina single JavaScript object called the "store"
2. What is a store and what do we use our reducers for within that store?
  - Store holds the complete state tree of an application. Reducres, on the other hand, are functions responsible for specifying how the application state changes in response to dispatched actions.Overall, the store manages the state, while reducers specify how the state should change in response to actions. 
3. Name three Redux store methods given to us by createStore and describe their use.
  - getState():
    -  eturns the current state held by the Redux store. It allows you to retrieve the current application state at any point in your code. By calling getState(), you can access the entire state object or specific properties within it. This method is useful for reading the state and using it to make decisions or display information in your application.
  - dispatch():
    - used to dispatch actions to the Redux store. When an action is dispatched, it triggers the state update process, where the reducers process the action and generate a new state. You pass an action object as an argument to dispatch(), which typically has a type property to describe the action and any additional payload data. This method is how you trigger state changes in Redux.
  - subscribe():
    -  allows you to register a listener function that will be called whenever the state in the Redux store changes. The listener is invoked after the state has been updated. It provides a way to react to state changes and update your application's UI or trigger other side effects. The subscribe method returns a function that you can call to unsubscribe the listener when you no longer need it. This method is useful for keeping your application in sync with the state and responding to changes accordingly.
4. Explain to a non-technical recruiter what combineReducers() does and why it is useful.
  - In Redux, combineReducers() is like putting together a team of experts for a project. Each expert focuses on their specific task, and similarly, each reducer function in Redux handles a different part of the application state. combineReducers() brings all these reducers together to form a unified team, making it easier to manage the state. It keeps the code organized and allows developers to work on different parts of the state independently. Think of it as assembling a team of specialists who work together smoothly to handle different aspects of the project, ensuring a well-organized and efficient state management in Redux.

## Things I want to know more about
