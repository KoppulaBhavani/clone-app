# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
node_modules
contains all the installed npm packages -> npm install 
you should never edit anything here
automatically created after npm install
npm create vite@latest ./-template react
npm install -> install dependency 
npm run dev -> for serve 
cd directory name  
public -> images 
src -> source code lives here
component:its resuable piece of ui that can be used anywhere in your application. basically it is a function that return jsx. component should be wrap with parent element
React component:
can accept data as input(these are called props);
can manage there own file

props -> passing external

jsx- it is a syntx extenstion for js used in react  to write html like code in js file
functions 
class functions : older way (not used often now)


Es module :
Named 
export const add = (a,b) => a+b 

Default :
export default function greet(name){
    return `hello ${world}`
}
import :
named:
import {add} from './'
default:
import greet  from './'

state:
built in object it allows components to hold and manage data
its triggers the rerender-again updateing
useState-> to update the state

useEffect-> it allows u to perform side effects in your component 
side effects are operatiions that effect something outside the scope  of the function  beign executed 
fecting data from api 
setting up timer 
directly update the dom
subscribing the socket 


