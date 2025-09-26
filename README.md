1/What is JSX, and why is it used?
Anwswer : JSX is a syntax extension for JavaScript that allows developers to write HTML like code directly within their JavaScript file.
Why used:
a) Improve Readability and Maintainability
b)Declaractive UI Description
c)Embedding JavaScript Expressions
d)Enhanced Error

2/What is the difference between State and Props?
Answer : 
Props : 
a) Source passed from parent to child component.
b) Can not changed
c) Controlled by parent component
State :
a) Managed internally by the component itself
b) Can changed
c) Controlled by component itself


3/What is the useState hook, and how does it work?
Answer : The useState hook in React is a function that lets function components manage their own internal data or state which can change over time.
How Works :
a)Initialize
b)Return Value
c)Array Destructuring
d)Updating State
Example : 
const [count, setCount] = useState(0);
<button onClick={() => setCount(count + 1)}>Click Me
</button>


4/How can you share state between components in React?
Answer : 
a) Initialize a React Application
b) Switch to the Project Directory
c) Creating Context
d) Creating set of data
e) Wrapping the app component
f) Accessing and Updating the Context
g) Access in another Component


5/How is event handling done in React?
Answer : Event handling in React is performed using a synthetic event system that offers a cross-browser compatible and efficient way to manage user interactions.

Example :
function HandleButton() {
      function handleClick() {
        console.log('Button clicked!');
      }

return (
<button onClick={handleClick()}> Click Me </button>
 );
}






















# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
