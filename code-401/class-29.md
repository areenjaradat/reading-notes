# Routing

1. Do child components have direct access to props/state from the parent?

 don't have direct access

2. When a component “wraps” another component, how does the child component’s output get rendered?

props.children

3. Can a component, such as <Content />, which is a child also be used as a standalone component elsewhere in the application?

Yes

4. What trick can a parent use to share all props with it’s children

props

## Term

props.children : In reactjs props.children is used to add the data between the opening and closing JSX tags.

composition : component have children (this the idea of composition ) that will give ability to git any thing put inside a component .

### React Router

* React Router has been broken into three packages: react-router, react-router-dom, and react-router-native.

* npm install --save react-router-dom

* `<BrowserRouter> `should be used when you have a server that will handle dynamic requests (knows how to respond to any possible URI), while the `<HashRouter>` should be used for static websites 

* The `<Route>` component is the main building block of React Router. Anywhere that you want to only render content based on the location’s pathname, you should use a `<Route>` element.

* `<Route>`s can be created anywhere inside of the router, but often it makes sense to render them in the same place. You can use the `<Switch>` component to group `<Route>`s. The `<Switch>` will iterate over its children elements (the routes) and only render the first one that matches the current pathname.

### Hooks

* React Hooks are a new addition in React 16.8 that let you use state and other React features without writing a class component. In other words, Hooks are functions that let you “hook into” React state and lifecycle features from function components. (They do not work inside class components.)
