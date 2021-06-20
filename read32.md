### What does a component’s lifecycle refer to?
 React lifecycle methods as the series of events that happen from the birth of a React component to its death. Every component in React goes through a lifecycle of events. I like to think of them as going through a cycle of birth, growth, and death
### Why do you sometimes need to “wrap” functions in useCallback when called from within useEffect

useCallback will help in avoiding regeneration of functions when the functional component re-renders
### Why are functional components preferred over class components?

functional component are much easier to read and test because they are plain JavaScript functions without state or lifecycle-hooks.



### state hook
A Hook is a special function that lets you “hook into” React features. For example, useState is a Hook that lets you add React state to function components.

### effect hook
The Effect Hook lets you perform side effects in function components: import React, { useState, useEffect } from 'react'; function Example() { const [count, setCount] = useState(0); // Similar to componentDidMount and componentDidUpdate: useEffect(() => { // Update the document title using the browser API document.

### reducer hook
 is a hook I use sometimes to manage the state of the application. ... It acts as an alternate hook to the useState hook to manage complex state in your application.

































