# Hooks API

### Review, Research, and Discussion

1. Why do we not need more .html pages in a multi-page React app?
Becuase we are using react-router-dom

2. If we wanted a component to show up on every page, where would we put it and why?

Inside the <BrowserRouter />, outside a <Route />

3. What does props.children contain?
props. children does is that it is used to display whatever you include between the opening and closing tags when invoking a component. 

### Terms

**Composition**: is the act of combining parts or elements to form a whole. Components are the UI building blocks in React applications, like pure functions are the building blocks of function composition.

**Children / Child Components**: Children allow you to pass components as data to other components, just like any other prop you use. ... The special thing about children is that React provides support through its ReactElement API and JSX. XML children translate perfectly to React children!

**Hash Routing**: is using the anchor part of the URL to simulate different content.

**Link Routing**: is a technique in which each router shares the knowledge of its neighborhood with every other router in the internetwork.


### Preparation Materials

**Hooks** are functions that let developers "hook into" React state and lifecycle features from function components.

**Built-in hooks:**
* useState
* useContext
* useReducer
* useEffect

**Rules of hooks**
1. Hooks should only be called at the top level (not inside loops or if statements).
2. Hooks should only be called from React function components, not normal functions or class components.

**The Effect Hook** lets you perform side effects in function components.

#### Resources
1. medium.com
2. stackoverflow.com
3. krasimirtsonev.com
4. www.javatpoint.com
5. Wikipedia
6. reactjs.org
7. 