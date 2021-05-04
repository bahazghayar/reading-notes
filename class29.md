# Routing

### Review, Research, and Discussion

1. Do child components have direct access to props/state from the parent?
There is no way to pass props from a child component to a parent component. However, we can always pass around functions from the parent to child component. The child component can then make use of these functions. The function can then update the state in a parent component

2. When a component “wraps” another component, how does the child component’s output get rendered?

                <Main>
                <Content />
                </Main>
By putting it inside props.children

3. Can a component, such as `<Content />`, which is a child also be used as a standalone component elsewhere in the application?
Yes

4. What trick can a parent use to share all props with it’s children
When you have a React component who received some props (“properties”) from its parent component, and you want to pass all of those props on to this component’s child, then you need to pass the entire props object.
If you happen to know all of the props, then you could pass them all by just listing them out individually as the new props for the child component.

### Terms

**props.children**: it is used to display whatever you include between the opening and closing tags when invoking a component. A simple example: Here's an example of a stateless function that is used to create a component.

**composition**: is one of the fundamental concepts in object-oriented programming. It describes a class that references one or more objects of other classes in instance variables. This allows you to model a has-a association between objects.


### Preparation Materials

React Router v4 is a pure React rewrite of the popular React package. Previous versions of React Router used configuration disguised as pseudo-components and could be difficult to understand. With v4, everything is “just components”.

React Router ships with a few hooks that let you access the state of the router and perform navigation from inside your components.

Queries are the methods that Testing Library gives you to find elements on the page. There are several types of queries ("get", "find", "query"); the difference between them is whether the query will throw an error if no element is found or if it will return a Promise and retry. Depending on what page content you are selecting, different queries may be more or less appropriate. See the priority guide for recommendations on how to make use of semantic queries to test your page in the most accessible way.

#### Resources
1. www.pluralsight.com
2. medium.com
3. stackoverflow.com
4. stackify.com
5. blog.pshrmn.com
6. reactrouter.com
7. testing-library.com