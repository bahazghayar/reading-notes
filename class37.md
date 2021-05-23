# Redux - Combined Reducers

### Review, Research, and Discussion

1. Why choose Redux instead of the Context API for global state?
It's better to use Redux, it is a better way to control state for large scale application.

2. What is the purpose of a reducer?
A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. We have tools, like Redux, that help manage an application's state changes in a single store so that they behave consistently.

3. What does an action contain?
Actions have a type field that tells what kind of action to perform and all other fields contain information or data. And there is one other term called Action Creators, these are the function that creates actions. So actions are the information (Objects) and action creator are functions that return these actions.

4. Why do we need to copy the state in a reducer?
Because the state is immutable in Redux

### Terms

**immutable state**: Immutable state is state that cannot be changed. Immutable objects (for which none of the state can be changed) become important when you are dealing with concurrency, the ability for more than one processor in your computer to operate on that object at the same time.

**time travel in redux**: The Redux DevTools records dispatched actions and the state of the Redux store at every point in time. This makes it possible to inspect the state and travel back in time to a previous application state without reloading the page or restarting the app

**action creator**: is merely a function that returns an action object. Redux includes a utility function called bindActionCreators for binding one or more action creators to the store's dispatch() function.

**reducer**: is a pure function that takes the current state and an action, and returns the next state. Note that the state is accumulated as each action on the collection is applied to change this state. So given a collection of actions , the reducer is applied on each value of the collection (from left-to-right).

**dispatch**:
Dispatch is the act of sending something somewhere. In computer science, this term is used to indicate the same concept in different contexts, like to dispatch a call to a function, dispatch an event to a listener, dispatch an interrupt to a handler or dispatch a process to the CPU.

### Preparation Materials

**combineReducers** is simply a utility function to simplify the most common use case when writing Redux reducers.

The state produced by combineReducers() namespaces the states of each reducer under their keys as passed to combineReducers()

#### Resources 
1. css-tricks.com
2. www.geeksforgeeks.org
3. softwareengineering.stackexchange.com
4. medium.com
5. read.reduxbook.com
6. stackoverflow.com
7. redux.js.org
