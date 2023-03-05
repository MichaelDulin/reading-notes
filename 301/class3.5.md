# Class 3.5 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 5**
- [React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
- [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

**React Docs - Thinking in React**
1. What is the single responsibility principle and how does it apply to components?
  -every class, module or function in a program should have one responsibility or purpose 
2. What does it mean to build a ‘static’ version of your application?
  - Static is hard-coded data into your code
3. Once you have a static application, what do you need to add?
  - Identify minimal (complete) representation of UI state
4. What are the three questions you can ask to determine if something is state?
  - Is it passed in from a parent via props? If so, it probably isn’t state.
  - Does it remain unchanged over time? If so, it probably isn’t state.
  - Can you compute it based on any other state or props in your component? If so, it isn’t state.
5. How can you identify where state needs to live?
  - Identify which components mutates or owns the state :
    - Identify every component that renders something based on that state.
    -  Find a common owner component (a single component above all the components that need the state in the hierarchy).
    -  Either the common owner or another component higher up in the hierarchy should own the state.
    -  If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
  
  
**Higher-Order Functions**
1. What is a “higher-order function”?
  - Functions which operate on other functiuons 
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
  - returns m if m is greater than n, which is the number passed 
3. Explain how either map or reduce operates, with regards to higher-order functions.
  - Both map and reduce use a callback to manipulate or filter code. Because we pass it a function, it is a higher-order function



## Things I want to know more about
