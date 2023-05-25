# Class 4.39 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 39**
- [Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)
- [MobX](https://mobx.js.org/getting-started.html)
- [Tutorial](https://redux-toolkit.js.org/tutorials/intermediate-tutorial)
- [HookState](https://hookstate.js.org/)

**Redux Toolkit (RTK)**
1. What concerns are addressed by Redux Toolkit?
  - Redux Toolkit addresses concerns such as boilerplate code, configuration, and best practices by providing a simplified and opinionated approach to Redux setup and usage.
2. What does configureStore() do?
  -  configureStore() is a function provided by Redux Toolkit that creates a Redux store with sensible default configuration, including middleware setup and support for dev tools.
3. How would I use createSlice()?
  -  createSlice() is a function from Redux Toolkit that helps in generating slice reducers. It combines reducer logic and action creators, reducing the boilerplate code typically associated with creating reducers.

****
  
**MobX**
1. What is Mobx?
  - MobX is a state management library that enables reactive programming by automatically tracking and updating the state in response to changes, simplifying the process of building reactive applications.
2. How does MobX make it “impossible” to produce an inconsistent state?
  - MobX ensures a consistent state by tracking the dependencies between observables and automatically updating any derived values or reactions when the observables change, eliminating the risk of inconsistencies.
3. How would we build a reactive user interface?
  - In MobX, you can build a reactive user interface by using observables to track state changes, and reactions to automatically update and synchronize components with the state changes. By marking components as observers, they will re-render whenever the relevant observables change, ensuring a reactive UI.

****

**Tutorial**
1. What take-away(s) did this tutorial provide?
  - Redux Toolkit provides a set of tools and utilities to simplify Redux development, including a concise API, automatic state immutability, simplified store setup with configureStore(), and simplified reducer logic with createSlice().
  - Redux Toolkit encourages writing Redux code in a more modern and efficient way, reducing boilerplate and promoting best practices, making it easier and faster to develop and maintain Redux applications.


## Things I want to know more about
