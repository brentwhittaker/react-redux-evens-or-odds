# react-redux-evens-or-odds
React-redux app for playing a simple card guessing game

## Redux concepts
- **Redux** is a state management technology. It handles all the underlying data for your React application by enforcing a universal flow of data - that components can read from and add to using dispatchable actions.

- The **Store** is the global object that collects all the data for a React application.

- **Reducers** split up the store and describe how sections of the store should update.

- **Actions** are objects full of data that the reducers listen to. These actions are dispatchable by components. And reducers will then use the action data to update the redux store.

- **React Redux** provides the connection between the redux system and the React components. Particularly, the Provider component gives each component access to the redux store. And the connect function allows each component to customize what parts of the redux store it wants to read, and what actions the component should be able to dispatch.

- **MapStateToProps**, parameter one of the react-redux connect function customizes which part of the redux store the component will have access to.

- **MapDispatchToProps**, parameter two of the react-redux connect function specifies which action creators the component should be able to dispatch.

- **Redux Middleware** code runs in between the point that an action gets dispatched and the reducers receive the action objects. Think of it as extensions for the redux system; it’s useful for adding new capabilities to the underlying redux logic. One such middleware is redux-thunk.

- **Redux thunk** is a library that allows for asynchronous actions to be dispatched. Normally, actions are plain objects. But in the case of using the fetch method, to make an api call, an asynchronous action is useful in order to dispatch different kinds of actions based on the result of the api call.

- **LocalStorage** is a JavaScript object that can be used to store items in a key-value structure within the browser.
