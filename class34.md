# `<Login />` and `<Auth />`

### Review, Research, and Discussion

1. Why is the Context API useful?
The Context API is a component structure provided by the React framework, which enables us to share specific forms of data across all levels of the application. It's aimed at solving the problem of prop drilling. ... Libraries like Redux allows you to get data from the store easily, anywhere in the tree.

2. Can a component outside of a provider get its context?
No.

3. What are some common use cases for using the Context API?
* Themes: The ability to set the theme is one of the best UX.
* Multilingual application: To implement multiple languages in app we have to change the text in every component and replace with the translated text.
* Authorisation: setting the user role and info.

4. Describe “Context Hell”
Context hell is the nasty code you get taking advantage of the React Context API.

### Terms

* **global state**: are used when components need to share states. React provides a very good and simple way to manage local state(React hooks) but when it comes to global state management the options available are overwhelming.

* **global context**: is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language. For example, in the code below we manually thread through a “theme” prop in order to style the Button component: class App extends React.

* **provider**: The `<Provider>` component makes the Redux store available to any nested components that need to access the Redux store. Since any React component in a React Redux app can be connected to the store, most applications will render a `<Provider>` at the top level, with the entire app's component tree inside of it.

* **consumer**:  `<MyContext.Consumer>` {value => /* render something based on the context value */} `</MyContext.Consumer>` A React component that subscribes to context changes. Using this component lets you subscribe to a context within a function component.


### Preparation Materials

**Role-based access control (RBAC)** restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.

**Benefits of RBAC:**
1. Reducing administrative work and IT support.
2. Maximizing operational efficiency.
3. Improving compliance.

**react-cookie** provides a `<CookieProvider>` component that you wrap around your root `<App>` component. This sets a cookies object, and allows us to start using cookies anywhere within this component. ... Import the component with import { CookiesProvider } from 'react-cookie'; . App.js. Now, within App.

#### Resources
1. blog.pusher.com
2. blog.bitsrc.io
3. dev.to
4. reactjs.org
5. react-redux.js.org
6. digitalguardian.com
7. rossbulat.medium.com