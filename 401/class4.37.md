# Class 4.37 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 37**
- [Multiple Reducers Example]()
- [Redux Docs: Using Combined Reducers]()

**Multiple Reducers Example**
1. Why create multiple reducers?
  - Creating multiple reducers in Redux provides modularity, scalability, reusability, and separation of concerns. It enhances code organization, promotes collaboration, and allows for more efficient and manageable state management as your application grows.
2. How would you combine multiple reducers?
  - Import combineReducers from Redux library
  - Create individual reducers for different parts of your applications state
  - Use the combineReducers() function to combine these individual reducers into a single reducer
  - Finally, you can create the Redux store using the combined reducer
3. How will you manage state as an immutable object? why?
  - In Redux, state is typically managed as an immutable object. This means that once the state is created, it cannot be changed. Instead, any modifications to the state result in the creation of a new state object. This leads to:
    - Predictability and debugging
    - Improved Performance
    - Concurrency and determinism
    - Function programming paradigm

****


**Redux Docs: Using Combined Reducers**
1. combineReducers is a utility function to simplify the most common use case when writing ___ _____ .
  - reducer functions.
2. Explain how combineReducers assembles the new state tree.
  - When you use the combineReducers() function in Redux, it assembles the new state tree by calling each individual reducer and combining their results:
    - Setting up the initial state:
      - When you create the Redux store and use combineReducers(), the initial state is set up by invoking each individual reducer with an undefined state and an empty action. This allows each reducer to return its initial state.
    - Dispatching actions:
      -  When an action is dispatched to the Redux store, the combined reducer created by combineReducers() calls each individual reducer with the current state slice and the dispatched action.
    - Handling state updates:
      -  Each individual reducer receives the corresponding state slice and the dispatched action. It examines the action's type and decides how to update its slice of the state based on that action.
    - Creating the new state tree:
      -  After all individual reducers have been called, they each return their updated state slice. combineReducers() collects these updated state slices and combines them into a new state tree.
    - Structure of the new state tree: 
      -  The new state tree generated by combineReducers() maintains the same structure as the individual state slices provided by each reducer. Each state slice becomes a property in the new state tree, with the same key names used in the combineReducers() configuration.
    - Returned state:
      -  The combined reducer returns the new state tree, which becomes the updated state of your Redux store. Components subscribed to the store will be notified of the state change and can access the updated state through getState().
3. How would you define initial state in an app using combineReducers?
  - When using combineReducers() in Redux, the initial state is defined by each individual reducer. Each reducer specifies its initial state as the default value assigned to its corresponding state slice. Here's how you can define the initial state in an app using combineReducers():
    -  Create individual reducer functions that handle different parts of the state and specify their initial states. Each reducer should have a default state value.
    -  Import the individual reducers and combine them using combineReducers(). The keys used to combine the reducers will correspond to the state slices they handle.

****

**Redux Docs: Combined Reducer Syntax**
1. Why will you want to split your reducing functions as your app becomes more complex?
  - Splitting reducing functions into separate reducers as an app becomes more complex promotes modularity, organization, separation of concerns, scalability, reusability, performance optimization, and ensures a single source of truth for the application state. These advantages help manage complexity, improve maintainability, and enhance the overall development experience.
2. The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.
  - The "combineReducers" helper function turns an object whose values are different reducing functions into a single reducing function you can pass to the Redux store's "createStore" method.
3. What is a popular convention when naming reducers?
  - A popular convention when naming reducers in Redux is to use descriptive names that reflect the state slice they handle. This convention helps to improve code readability and maintainability


## Things I want to know more about
