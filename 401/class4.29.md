# Class 4.29 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 29**
- [Extracting State Logic into a Reducer](https://react.dev/learn/extracting-state-logic-into-a-reducer)
- [useReducer hook](https://react.dev/reference/react/useReducer)
- [Keeping Components Pure](https://react.dev/learn/keeping-components-pure)
- [Queueing a Series of State Updates](https://react.dev/learn/queueing-a-series-of-state-updates)

**Extracting State Logic into a Reducer**
1. What is the motivation for adding a reducer?
  - It may be useful to use a reducer as the complexity and number of components grow to consolidate the state logic outside of the component. This allows us to view state in a more organized way rather than skimming though multiple components.
2. What are actions in the context of a reducer? How are they different than setting state directly?
  - Rather than setting task via an event handler, we can instead pass an action, which is an object describing what occured. This is more descriptive and allows us to see more detail as state changes.
3. What common list operation is useReduce named for, and why?
  - Reduce() as they too skim through many things and pull out a single, accumulated object.
4. When should you switch from useState to useReducer?
  - Consider utilizing useReduce() when handling many operations within a component.

## Things I want to know more about
