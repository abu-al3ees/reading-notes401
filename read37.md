### Why choose Redux instead of the Context API for global state?
Context API is easy to is use as it has a short learning curve. It requires less code, and because there's no need of extra libraries, bundle sizes are reduced. Redux on the other hand requires adding more libraries to the application bundle. The syntax is complex and extensive creating unnecessary work and complexity.‏

### What is the purpose of a reducer?
A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently.

### What does an action contain?
Actions are the only source of information for the store as per Redux official documentation. It carries a payload of information from your application to store. const ITEMS_REQUEST = 'ITEMS_REQUEST'; Apart from this type attribute, the structure of an action object is totally up to the developer.



### immutable state
State cannot be modified, reducers must make copies of existing state to make updates
### time travel in redux
l debugging refers to the ability step forward and backward through the state of you application, empowering the developer understand exactly what is happening at any point in the app's lifecycle
### action creator
is merely a function that returns an action object. Redux includes a utility function called bindActionCreators for binding one or more action creators to the store's dispatch() function
---------------------------------------
### The combineReducers
 helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore . The resulting reducer calls every child reducer, and gathers their results into a single state object

### how we use it 
It turns out that Redux lets us combine multiple reducers into one that can be passed into createStore by using a helper function named combineReducers . The way we combine reducers is simple, we create one file per reducer in the reducers directory. We also create a file called index. js inside the reducers directory.
