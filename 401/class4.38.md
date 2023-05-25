# Class 4.38 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 38**
- [async actions](https://redux.js.org/advanced/asyncactions)
- [thunk middleware](https://github.com/reduxjs/redux-thunk)

****

**async actions**
1. Why use Redux middleware?
  - Redux middleware extends Redux's capabilities by intercepting actions and allowing for additional logic or side effects, such as handling asynchronous operations and performing tasks like logging or analytics.
2. Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.
  - Async actions are intercepted by middleware, which can perform asynchronous operations. Afterward, a new action with the result/error is dispatched. The reducers update the state based on the action, and the updated state is reflected in the UI.
3. How are we accommodating async in our Redux app?
  - We use middleware like Redux Thunk, Redux Saga, or Redux Observable to handle async operations. For example, with Redux Thunk, we write action creators that return functions instead of plain action objects, allowing for async logic and dispatching multiple actions if needed.

****
  
**thunk middleware**
1. Why would you need redux-thunk middleware?
  - Redux Thunk middleware is used to dispatch asynchronous actions in Redux, enabling the use of action creators that return functions instead of plain action objects.
2. Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.
  - Redux Thunk middleware allows you to write action creators that return a function instead of an action.
3. Describe how any return value from the inner thunk function will be made available.
  - The return value from the inner thunk function is not automatically accessible outside the thunk. You can handle it using promises, async/await, or by dispatching actions with the return value as part of the payload, which can then be used by reducers to update the state.


## Things I want to know more about
