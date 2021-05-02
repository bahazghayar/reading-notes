# Component Composition

### Review, Research, and Discussion

1. Can a parent component access the state of a child component?
In React we can access the child's state using Refs. we will assign a Refs for the child component in the parent component. then using Refs we can access the child's state.
Creating Refs Refs are created using React.createRef() and attached to React elements via the ref attribute.

2. What can be passed along in a prop variable?
Props can be anything, integers over objects to arrays or a string.

3. How can a child component “know” the state of another component?
To obtain the state of another component, you can pass a component's state to its child components as props. Also, you can have components share a common ancestor, and have them access the same state in a similar manner.

### Terms

**component props**: Props are arguments passed into React components. Props are passed to components via HTML attributes.

**component state**: The state is an instance of React Component Class can be defined as an object of a set of observable properties that control the behavior of the component. In other words, the State of a component is an object that holds some information that may change over the lifetime of the component.

**application state**: Application State (also known as Program State) represents the totality of everything necessary to keep your application running. When we refer to application state we are normally referring to the state of the program as it exists in the contents of its memory.


### Preparation Materials

**These are the concepts you should know in React.js**:
1. The Component Lifecycle
* Mounting
* Updating
* Unmounting

2. Higher-Order Components
3. React State and setState()
4. React Context



#### Resources
1. www.geeksforgeeks.org
2. medium.com
3. discuss.codecademy.com
4. www.w3schools.com
5. thedaylightstudio.com
6. www.freecodecamp.org