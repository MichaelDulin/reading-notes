# Class 4.26 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 26**
- [React Quick Start](https://react.dev/learn)
- [Render and Commit](https://react.dev/learn/render-and-commit)

**Additional Resources**
- [Your First Component](https://react.dev/learn/your-first-component)
- [Importing and Exporting Components](https://react.dev/learn/importing-and-exporting-components)
- [Writing Markup with JSX](https://react.dev/learn/writing-markup-with-jsx)
- [sass cheatsheet](https://devhints.io/sass)
- [react cheatsheet](https://devhints.io/react)
- [Airbnb React/JSX Style Guide](https://airbnb.io/javascript/react/#naming)



**React Quick Start**
1. What are the building blocks of a React app?
  - Components
2. What is the difference between an HTML element and a React component?
  - An HTML element is standardized and must adhere to HTML rules. A component is a resusable piece of code which can contain a multitude of varying data such as functions, classes or objects.
3. What is JSX and why do we use it?
  - The return value of a React component.
4. Describe the process of embedding JavaScript expressions in JSX.
  - Must wrap all return values in a wrapper such as div or <></>. Must wrap JS data in curly brackets.
5. Does React or JSX have any special features for iteration or conditional logic?
  - Cannot loop or set conditionals using React, rather, we must use JavaScript to do so, and even then there are only a few options.
6. How does React know to respond to a user’s inputs?
  - Event listeners
7. What word indicates that a React component manages data with a Hook?
  - useState
8. How can two react components share data?
  - By importing/exporting the component module, or, if direct child of other component.

  
**Render and Commit**
1. What are the three steps of refreshing a React UI?
  - Triggering a render (delivering the guests order to the kitchen)
  - Rendering the component (preparing the order in the kitchen)
  - Committing to the DOM (placing the order on the table)
2. How do you trigger updates to a component after the initial render?
  - With Hooks: useState
  - W/o Hooks: setState
3. Does React recreate DOM nodes on every rerender?
  - No, it will apply the changes with the minimal necessary operations needed to match the DOM with new values to previous version of DOM
4. After React has updated the DOM, what still needs to happen before the user sees the change?
  - The browser must render


## Things I want to know more about
