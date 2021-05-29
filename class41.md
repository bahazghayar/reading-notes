# React Native

### Review, Research, and Discussion

1. Compare and Contrast Redux Toolkit with Redux “Ducks”

**Redux Toolkit** is our official, opinionated, batteries-included toolset for efficient Redux development. It is intended to be the standard way to write Redux logic, and we strongly recommend that you use it.

It includes several utility functions that simplify the most common Redux use cases, including store setup, defining reducers, immutable update logic, and even creating entire "slices" of state at once without writing any action creators or action types by hand. It also includes the most widely used Redux addons, like Redux Thunk for async logic and Reselect for writing selector functions, so that you can use them right away.

It outlines a strategy called **‘Ducks’** which lays out a way to organize a React/Redux file system at a large scale.
The basic idea behind Ducks is to create a file structure that is scalable and easy to follow.

2. What is the principle advantage of Redux Toolkit
Redux Toolkit makes it easier to write good Redux applications and speeds up development, by baking in our recommended best practices, providing good default behaviors, catching mistakes, and allowing you to write simpler code.

### Terms

**redux toolkit slices**: A function that accepts an initial state, an object full of reducer functions, and a "slice name", and automatically generates action creators and action types that correspond to the reducers and state.

**namespace**: Namespace refers to the programming paradigm of providing scope to the identifiers (names of types, functions, variables, etc) to prevent collisions between them. For instance, the same variable name might be required in a program in different contexts. Using namespaces in such a scenario will isolate these contexts such that the same identifier can be used in different namespaces. In this article, we will discuss how namespaces can be initialized and used in JavaScript. JavaScript does not provide namespace by default. However, we can replicate this functionality by making a global object which can contain all functions and variables.


### Preparation Materials

**React Native** is like React, but it uses native components instead of web components as building blocks. So to understand the basic structure of a React Native app, you need to understand some of the basic React concepts, like JSX, components, state, and props. If you already know React, you still need to learn some React-Native-specific stuff, like the native components. This tutorial is aimed at all audiences, whether you have React experience or not.

**Expo** is a framework and a platform for universal React applications. It is a set of tools and services built around React Native and native platforms that help you develop, build, deploy, and quickly iterate on iOS, Android, and web apps from the same JavaScript/TypeScript codebase.

#### Resources
1. medium.com
2. redux.js.org
3. redux-toolkit.js.org
4. www.geeksforgeeks.org
5. docs.expo.io
6. reactnative.dev