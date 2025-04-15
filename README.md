# Material Design Web CSS Libary

Experimental attempt to make "Material Design Web" simple and without all those BlingBling from modern Libarys.
(To write even Libarys with stuff like Lit, Sass and other stuff, which are only exist to reduse some lines of code, is simple the wrong future.)

First I thought about to rewrite it as pure Web Components without BlingBling, React Components (would be reduce performance) but than I found out the power of pure css by simple write css for classes and already existing elemts.

# How it will work

Actlually simple include the css you need.

Imagine you want a checkbox, simple include the css by  
`import './material-css/checkbox.css';`  

If you now use the default html element it will be the material checkbox  
`<input type="checkbox" ... />`

# Test Sandbox

Use the `index.html` to test (typical node+vite enviroment)

Use the `material-web-sandbox.html` (standalone) to compare with the original material-web lib.

# Roadmap

1. rewrite every [material-web](https://github.com/material-components/material-web)
3. Full pure react example (node+vite,react,pocketbase)
2. create a npm package