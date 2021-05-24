# Redux - Asynchronous Actions

Review, Research, and Discussion

1. How granular should your reducers be?
I would say that the default solution would be that a change of any of those attributes would trigger a separate kind of action such as CHANGE_EMAIL or CHANGE_NAME. 

2. Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched
Con

3. Name a strategy for preventing the above
By using more specific name.

### Term
**store**:  store holds the whole state tree of your application. The only way to change the state inside it is to dispatch an action on it. A store is not a class. It's just an object with a few methods on it. To create it, pass your root reducing function to createStore .

**combined reducers**: The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore . The resulting reducer calls every child reducer, and gathers their results into a single state object.

### Preparation Materials

**Redux Thunk** is a middleware that lets you call action creators that return a function instead of an action object. That function receives the store's dispatch method, which is then used to dispatch regular synchronous actions inside the function's body once the asynchronous operations have been completed.

#### Resources
1. reactkungfu.com
2. redux.js.org
3. www.digitalocean.com