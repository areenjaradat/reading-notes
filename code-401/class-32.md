# Custom Hooks

## Review, Research, and Discussion

1. **What does a component’s lifecycle refer to?**

Lifecycle of a component is series of methods that are invoked in different stages of the component's existence. Lifecycle methods give ways to interact with component logic before/during/after being used in the DOM. (source: [GeeksforGeeks](https://www.geeksforgeeks.org/reactjs-lifecycle-components/))

2. **Why do you sometimes need to “wrap” functions in `useCallback` when called from within `useEffect`**

`useCallback()` is often used in conjunction with `useEffect()` because it allows you to prevent the re-creation of a function. (source: [Medium](https://medium.com/@infinitypaul/reactjs-useeffect-usecallback-simplified-91e69fb0e7a3) and [React docs](https://reactjs.org/docs/hooks-reference.html))

3. **Why are functional components preferred over class components?**

Functional components are much easier to read and test, they have less code, easier to separate container and presentational components. (source: [Medium](https://medium.com/wesionary-team/react-functional-components-vs-class-components-86a2d2821a22))

4. **What is wrong with the following code?**

`useEffect()` cannot be called inside a loop

## Vocabulary Terms

- **State hook**: ```useState()```, similar to ```this.setState()``` in a class except it doesn't merge the old and new state together. The only argument to ```useState()``` is the initial state. Allows us to add a state powered variable to our application. (source: [React docs](https://reactjs.org/docs/hooks-overview.html))
- **Effect hook**: ```useEffect()```, adds the ability to perform side effects (data fetching, subscriptions, or manually changing the DOM from React components) from a function component. Serves the same purpose as ```componentDidMount```, ```componentDidUpdate```, and ```componentWillUnmount``` in React classes but unified into a single API. Allows us to define properties that will trigger or not trigger React API features.
- **Reducer hook**: alternative to ```useState()```, accepts a reducer of type (state, action) => newState, and returns the current state paired with a dispatch method (method to dispatch actions and trigger state changes per [React Redux docs](https://react-redux.js.org/using-react-redux/connect-mapdispatch))
- Sources: React hooks [overview](https://reactjs.org/docs/hooks-overview.html) and [reference list](https://reactjs.org/docs/hooks-reference.html) and notes from CSS tricks on useReducer hook [here](https://css-tricks.com/getting-to-know-the-usereducer-react-hook/)

## Authoring

- [custom hooks - all you need to know](https://www.telerik.com/kendo-react-ui/react-hooks-guide/#toc-custom-react-hooks)

  - `useEffect` tells react to do something after the render is complete and after every update
  - `useEffect(()=>{document.title = 'You clicked ${count} times'});`
  - Custom hooks are prefixed with the word `use`, normal function but follows the rules of creating a Hook

- [async hooks](https://dev.to/vinodchauhan7/react-hooks-with-async-await-1n9g)

      - Offers an example of how to code a fetch request to google books
      - Cannot use `async` keyword with `useEffect` will create race condition

- [useReducer Hook](https://reactjs.org/docs/hooks-reference.html#usereducer)
      - Reducer takes in `(state, action)` and returns current state and a dispatch method
      - Preferable when complex state logic or multiple sub-values or when state depends on previous

- [react custom hooks](https://reactjs.org/docs/hooks-custom.html)
       - When you want to share logic between two hooks, extract to a third hook
       - name must start with use
       - state inside custom hooks is isolated

## Hooks Lists/Collections

- [use hooks](https://usehooks.com/)
- [hooks list](https://github.com/rehooks/awesome-react-hooks)
- [10 essential react hooks](https://blog.bitsrc.io/10-react-custom-hooks-you-should-have-in-your-toolbox-aa27d3f5564d)