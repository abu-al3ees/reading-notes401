### Do child components have direct access to props/state from the parent?
yes

### When a component “wraps” another component, how does the child component’s output get rendered?
 
using  A higher-order component (HOC) is an advanced technique 

### Can a component, such as <Content />, which is a child also be used as a standalone component elsewhere in the application?

no ,standalone components have no parents to get props from or children to pass props to.

### What trick can a parent use to share all props with it’s children

use React.Children to iterate over the children, and then clone each element with new props (shallow merged) using React.cloneElement


### props.children
props. children is a special prop, automatically passed to every component, that can be used to render the content included between the opening and closing tags when invoking a component. These kinds of components are identified by the official documentation as “boxes”

### composition

 is a natural pattern of the component model. It's how we build components from other components, of varying complexity and specialization through props. Depending on how generalized these components are, they can be used in building many other components

## browser router
Routers. At the core of every React Router application should be a router component. For web projects, react-router-dom provides   BrowserRouter   and  HashRouter  routers. The main difference between the two is the way they store the URL and communicate with your web server. A   BrowserRouter  uses regular URL paths.



### Hooks
React Hooks are a new addition in React 16.8 that let you use state and other React features without writing a class component. In other words, Hooks are functions that let you “hook into” React state and lifecycle features from function components. (They do not work inside class components.)


























