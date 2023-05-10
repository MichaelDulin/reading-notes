# Class 4.28 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 28**
- [useEffect hook](https://react.dev/reference/react/useEffect#reference)
- [Responding to Events](https://react.dev/learn/responding-to-events)
- [Conditional Rendering](https://react.dev/learn/conditional-rendering)
- [Updating Arrays in State](https://react.dev/learn/updating-arrays-in-state)
- [Updating Objects in State](https://react.dev/learn/updating-objects-in-state)

****

**useEffect hook**
1. What is the main intended use case for the useEffect hook?
  - Invoking side effects from within functional components
2. How does the effect’s logic interact with the component?
  - Essentially leaves an open window for us to obesrve state as it is being updated i.e. count
3. What is the importance of the return value from the effect’s logic function?
  - The return function is the cleanup function, which is triggered when componentDidUnmount. This prevents bugs as this 'cleans' the screen for us on new render.


## Things I want to know more about
