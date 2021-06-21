### Describe use cases for useMemo() and useReducer()

The useMemo() hook is often used to optimize when doing expensive calculations while rendering. userReducer() can be used for managing state objects that contain multiple sub-values. UseReducer is an alternative to useState, usually preferable when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one.

### Why do custom hooks need the use prefix?

Should start with use so that you can tell at a glance that the rules of Hooks apply to it.

### What do custom hooks usually do?

Allow you to extract and share logic in a way that was not possible with class components.



## The Context API 
is a React structure that enables you to exchange unique details and assists in solving prop-drilling from all levels of your application.

- Context
Context provides a way to pass data through the component tree without having to pass props down manually at every level.

The Context API can be used to share data with multiple components, without having to pass data through props manually. For example, some use cases the Context API is ideal for: theming, user language, authentication, etc.

### When to Use Context
Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.







