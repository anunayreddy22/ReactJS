# ReactJS
A simple short hand notes on ReactJS

What is React?

React is a JavaScript library that aims to simplify the development of visual interfaces.

React in itself has a very small API, and you basically need to understand 4 concepts to get started:

Components
JSX
State
Props


React Components

Most of the applications comes with a series of files that do various things, mostlyrelated to configuration, but there's one file that stands out: App.js .
App.js is the first React Component we go through.

// Sample Code

import React from 'react'
import logo from './logo.svg'
import './App.css'
function App() {
 return /* something */
}
export default App


we export a function called App.

The things we import in this case are a JavaScript library (the react npm
package), an SVG image, and a CSS file
















