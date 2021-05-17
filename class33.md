# Context API

### Review, Research, and Discussion

1. Describe use cases for useMemo() and useReducer()
**useMemo()** should be used when there is a high amount of processing. The threshold from when useMemo becomes interesting for avoiding extra processing highly depends on your application.

**useReducer()** is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

2. Why do custom hooks need the use prefix?
the "use" prefix helps in easily identifying if a function is a custom hook.

3. What do custom hooks usually do?
Custom Hooks are a mechanism to reuse stateful logic (such as setting up a subscription and remembering the current value), but every time you use a custom Hook, all state and effects inside of it are fully isolated.

4. Using any list of custom hooks, research and name one that you think will be useful in your applications.
useClippy : A hook for copying data to the clipboard and retrieving/pasting it using Ctrl-C/Command-C and Ctrl-V/Command-V.


5. Describe how a hook that fetches API data might work.
we're going to import stuff we're going to use and create a function. The next step is to add a useState hook and to define the name of the state - in our case, that's data. Then, we define the function we'll use later on to update the state - setData.


### Terms
* **reducer**: The reducer is a pure function that takes the current state and an action, and returns the next state. Note that the state is accumulated as each action on the collection is applied to change this state. So given a collection of actions , the reducer is applied on each value of the collection (from left-to-right).

### Preparation Materials

**Context** provides a way to pass data through the component tree without having to pass props down manually at every level.

**When to Use Context**
Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.

#### Resources
1. stackoverflow.com
2. reactjs.org
3. medium.com
4. blog.bitsrc.io
5. dev.to