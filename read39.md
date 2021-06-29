### 
The most 'redux-like' way of handling the pre-loading of data would be to fire off the asynchronous action in the lifecycle method (probably componentWillMount ) of a Higher Order Component that wraps your app


### When using a thunk/async action that dispatches the actual action, which do you export from your reducer?

 You can manage asynchronous actions in Redux with Thunk, or you ... Implementing this approach requires that you dispatch the action that ... That said​, you may be tempted to support asynchronous actions by modifying their reducers, ... actual action and the related synchronous actions to implement the ...


 ### middleware
 
Code you put in between the framework receiving a request and the framework generating the response.
### Thunk 
Function that wraps an expressio to delay its evaluation.


### Redux Toolkit 
is  official, opinionated, batteries-included toolset for efficient Redux development. ... It also includes the most widely used Redux addons, like Redux Thunk for async logic and Reselect for writing selector functions, so that you can use them right away.


the Redux Toolkit generates the new state from the direct changes to the old state. ... The reducers that are written with immer are 2 to 3 times slower than a normal Redux reducer


### Why do we need Redux toolkit?

It allows us to write more efficient code, speed up the development process, and automatically apply the best-recommended practices. It was mainly created to solve the THREE MAJOR ISSUES with Redux: Configuring a Redux store is too complicated. Have to add a lot of packages to build a large scale application.


### How do I use Redux toolkit with react?
Use Redux State and Actions in React Components

js file with a /Counter/ component inside, then import that component into App. js and render it inside of /App/ . Now, any time you click the "Increment" and "Decrement buttons: The corresponding Redux action will be dispatched to the store



















