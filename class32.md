# Custom Hooks

### Review, Research, and Discussion

1. What does a component’s lifecycle refer to?
We are born, grow, and then die. Almost everything follows this cycle in its life, and React components do as well. Components are created (mounted on the DOM), grow by updating, and then die (unmount on DOM). This is referred to as a component lifecycle.

2. Why do you sometimes need to “wrap” functions in useCallback when called from within useEffect?
useCallback will help in avoiding regeneration of functions when the functional component re-renders. However there isn't much of a performance difference caused by recreation of functions.

3. Why are functional components preferred over class components?
Functional component are much easier to read and test because they are plain JavaScript functions without state or lifecycle-hooks. You end up with less code. They help you to use best practices.

4. What is wrong with the following code?

The rules of Hooks clearly state: Don't call Hooks inside loops, conditions, or nested functions. Instead, always use Hooks at the top level of your React function. Hooks need to be called in the same order each time the component renders.

                    import React, {useState, useEffect} from 'react';

                    function MyComponent(props) {
                            const [count, setCount] = useState(0);

                            function changeCount(e) {
                                setCount(e.target.value);
                            }

                            let renderedItems = []

                            for (let i = 0; i < count; i++) {
                                useEffect( () => {
                                console.log('component mount/update');
                                }, [count]);

                                renderedItems.push(<div key={i}>Item</div>);
                            }

                            return (<div>
                                <input type='number' value={count} onChange={changeCount}/>
                                {renderedItems}
                                </div>);
                    }


### Terms

**state hook**: useState is a Hook that lets you add React state to function components.

**effect hook**: The Effect Hook lets you perform side effects in function components: import React, { useState, useEffect } from 'react'; function Example() { const [count, setCount] = useState(0); // Similar to componentDidMount and componentDidUpdate: useEffect(() => { // Update the document title using the browser API document.

**reducer hook**: The useReducer is a hook I use sometimes to manage the state of the application. It is very similar to the useState hook, just more complex. It acts as an alternate hook to the useState hook to manage complex state in your application. The useReducer hook uses the same concept as the reducers in Redux.


### Preparation Materials

Hooks are a new addition in React that lets you use state and other React features without writing a class. This website provides easy to understand code examples to help you learn how hooks work and inspire you to take advantage of them in your next project.

**Basic Hooks**
* useState
* useEffect
* useContext

**Additional Hooks**
* useReducer
* useCallback
* useMemo
* useRef
* useImperativeHandle
* useLayoutEffect
* useDebugValue

**10 React Hooks you Should Have in Your Toolbox**
1. useArray hook
2. react-use-form-state hook
3. react-fetch-hook
4. useMedia hook
5. react-useportal hook
6. react-firebase-hooks
7. use-onClickOutside hook
8. useIntersectionObserver hook
9. use-location hook
10. use-redux hook

#### Resources:
1. reactjs.org
2. adhithiravi.medium.com
3. blog.logrocket.com
4. www.freecodecamp.org
5. stackoverflow.com
6. djoech.medium.com
7. usehooks.com