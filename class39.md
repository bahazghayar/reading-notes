# Redux - Additional Topics

### Review, Research, and Discussion

1. What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?
The most 'redux-like' way of handling the pre-loading of data would be to fire off the asynchronous action in the lifecycle method (probably componentWillMount ) of a Higher Order Component that wraps your app.

2. When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
The actual action from the reducer.

### Term

**middleware**: allows for side effects to be run without blocking state updates. We can run side effects (like API requests) in response to a specific action, or in response to every action that is dispatched (like logging). There can be numerous middleware that an action runs through before ending in a reducer.

**thunk**: Redux Thunk is middleware that allows you to return functions, rather than just actions, within Redux. This allows for delayed actions, including working with promises. ... Redux Thunk allows us to dispatch those actions asynchronously and resolve each promise that gets returned.


#### Preparation Materials

**Redux Toolkit** is our official, opinionated, batteries-included toolset for efficient Redux development. It is intended to be the standard way to write Redux logic, and we strongly recommend that you use it.

It includes several utility functions that simplify the most common Redux use cases, including store setup, defining reducers, immutable update logic, and even creating entire "slices" of state at once without writing any action creators or action types by hand. It also includes the most widely used Redux addons, like Redux Thunk for async logic and Reselect for writing selector functions, so that you can use them right away.

**MobX** is a simple, scalable and battle tested state management solution. This tutorial will teach you all the important concepts of MobX in ten minutes. MobX is a standalone library, but most people are using it with React and this tutorial focuses on that combination.


#### Resources
1. stackoverflow.com
2. www.metaltoad.com
3. www.freecodecamp.org
4. redux.js.org
5. mobx.js.org