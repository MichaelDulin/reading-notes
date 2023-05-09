# Class 4.27 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 27**
- [Thinking in React](https://react.dev/learn/thinking-in-react)
- [State: A Component’s Memory](https://react.dev/learn/state-a-components-memory)
- [Passing Props to a Component](https://react.dev/learn/passing-props-to-a-component)
- [Rendering Lists](https://react.dev/learn/rendering-lists)
- [State as Snapshot](https://react.dev/learn/state-as-a-snapshot)
- [useState hook](https://react.dev/reference/react/useState)

****

**Thinking in React**
1. Summarize the five steps of thinking in react.
  - Break UI into a component hierarchy: 
  - Build a static version in React:
  - Find minimal complete representation of UI state: 
  - Identify where state should live: 
  - Add inverse data flow:

  
**State: A Component’s Memory**
1. What is one reason a local variable isn’t sufficient for managing a React component?
  - Local variables do not persist between renders and changes to a local variable wont trigger renders
2. What is the argument to the useState hook, and what are the two parts of its return array?
  - The state variable and the setter function
3. How can Component A access state from Component B?
  - State is private to the component and must be rendered individually unless passed off once state is set


## Things I want to know more about
