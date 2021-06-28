
### How granular should your reducers be?
It is difficult to manage states that are deeply nested, so more reducers is better than only a few. Redux gives us combineReducers to let us define more precisely what our initial state will look like.

### Name a strategy for preventing the above
Using Redux middleware thunk, allows for evaluating the actions.



### store :
Holds the whole state tree of the application, only way to change the state inside is to dispatch an action on it.
### combined reducers :
Helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.




### Redux Thunk 
is a middleware that lets you call action creators that return a function instead of an action object. That function receives the store's dispatch method, which is then used to dispatch regular synchronous actions inside the function's body once the asynchronous operations have been completed.




### Using Redux Thunk in a Sample Application
The most common use case for Redux Thunk is for communicating asynchronously with an external API to retrieve or save data. Redux Thunk makes it easy to dispatch actions that follow the lifecycle of a request to an external API.