# Context API - Behaviors

### 1. When you have multiple contexts, what component type should you use (class/function) and why?
- 

### 2. What are some good use cases for using the Context API for global state?
- 

### 3. How can you best test context?
- 

*** 
## Vocabulary Terms: 
| Term      | Definition                                                                                                 |
| --------- | ---------------------------------------------------------------------------------------------------------------|
| context
|A   function  |
| useContext()
|  The main job  |
 static context
|  The main job   |
*** 
 
## Preparation Materials:
 ### Context API

- **Context** provides a way to pass data through the component tree without having to pass props down manually at every level.

- Before You Use Context :Context is primarily used when some data needs to be accessible by many components at different nesting levels. Apply it sparingly because it makes component reuse more difficult.

- If you only want to avoid passing some props through many levels, component composition is often a simpler solution than context.

- Creates a Context object. When React renders a component that subscribes to this Context object it will read the current context value from the closest matching Provider above it in the tree.

- The defaultValue argument is only used when a component does not have a matching Provider above it in the tree. This can be helpful for testing components in isolation without wrapping them. Note: passing undefined as a Provider value does not cause consuming components to use defaultValue.

- Creates a Context object. When React renders a component that subscribes to this Context object it will read the current context value from the closest matching Provider above it in the tree.

- The defaultValue argument is only used when a component does not have a matching Provider above it in the tree. This can be helpful for testing components in isolation without wrapping them. Note: passing undefined as a Provider value does not cause consuming components to use defaultValue.


 *** 
#### Resources: 

* [context api](https://reactjs.org/docs/context.html)
* [hooks and context example](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)
* [react context links](https://github.com/diegohaz/awesome-react-context)




 

[Back](https://github.com/En-ZUH/Reading-notes/tree/main/401)
