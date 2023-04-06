# Class 4.3 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 3**
- [Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
- [Using Express Routing](https://expressjs.com/en/guide/routing.html)
- [Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)
- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-03/)

**Review: ES6 Classes**
1. Classes are a template for creating ____.
  - Objects
2. Can a class declaration be hoisted?
  - Class declarations are hoisted, however, they need to be declared before they can be used
3. How would you describe a constructor and contextual “this” to a non-technical friend?
  - A constructor defines what all should be included when we create a new object. When using 'this', we are refering to the current object being created in order to refrence it throughout the build process.

  
**Using Express Routes**
1. Within Express, what does routing refer to?
  - Refers to how an applications endpoints respond to client requests.
2. What is the difference between a route path and a route method?
  - Route paths define the the endpoints or where we want to look for objects within our code, while route methods specify a callback function to be executed when the route path reaches its destination
3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
  - Next can be used by route handlers when bypassing the remaining route callbacks



**Express Routing**
1. What is an Express Router?
  - Acts as a mini-Express application and provides us with routing API's such as use, get, param and route.
2. By what mean do we initialize express.Router() in an express server?
  - const router = express.Router();
3. What do we use route middleware for?
  - Middleware acts as a pre-check before requests are processed. This includes checking for authentication, or logging data.


**Reflection**
1. What are your learning goals after reading and reviewing the class README?
  - I would like to get more comfortable with writing express applications by hand. I understand the concepts, however, as of now it is a lot to write from scratch.


## Things I want to know more about
