# Hooks API

Why do we not need more .html pages in a multi-page React app?

 react-router-dom

If we wanted a component to show up on every page, where would we put it and why?
Outside the <BrowserRouter/>
Inside the <BrowserRouter />, outside a <Route />
Inside a <Route />

What does props.children contain?

props.children is used to add the data between the opening and closing JSX tags.

## Term

Composition  component have children (this the idea of composition ) that will give ability to git any thing put inside a component .

props.children : In reactjs props.children is used to add the data between the opening and closing JSX tags.

HashRouter: When we have small client side applications which doesn't need backend we can use HashRouter because when we use hashes in the URL/location bar browser doesn't make a server request.

## Hooks

Hooks are the new feature introduced in the React 16.8 version. It allows you to use state and other React features without writing a class. Hooks are the functions which "hook into" React state and lifecycle features from function components. It does not work inside classes.

Hooks are backward-compatible, which means it does not contain any breaking changes. Also, it does not replace your knowledge of React concepts.

<br/>
<br/>

## When to use a Hooks

If you write a function component, and then you want to add some state to it, previously you do this by converting it to a class. But, now you can do it by using a Hook inside the existing function component.

<br/>
<br/>

## Rules of Hooks

1. Only call Hooks at the top level

Do not call Hooks inside loops, conditions, or nested functions. Hooks should always be used at the top level of the React functions.

2. Only call Hooks from React functions

You cannot call Hooks from regular JavaScript functions. Instead, you can call Hooks from React function components. Hooks can also be called from custom Hooks.

<br/>
<br/>

## Pre-requisites for React Hooks

Node version 6 or above
<br/>
NPM version 5.2 or above
<br/>
Create-react-app tool for running the React App

## React Hooks Installation

To use React Hooks, we need to run the following commands:

        $ npm install react@16.8.0-alpha.1 --save  
        $ npm install react-dom@16.8.0-alpha.1 --save  

The above command will install the latest React and React-DOM alpha versions which support React Hooks.

## Hooks State

Hook state is the new way of declaring a state in React app. Hook uses useState() functional component for setting and retrieving state.