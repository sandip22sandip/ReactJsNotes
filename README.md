node -v
npm -v

React Developer Tools Chrome

Thunder Client,
ES7 React/Redux/GraphQL/React-Native snippest,
Auto Rename Tag,
Live Server,
Prettier - Code formatter

Create React App:-
npx create-react-app my-app / npx create-react-app .
cd my-app
npm start

Main Folders:-
src:- index.js, App.js
public:- index.html (Entry Point)

JSX inside App.js:-
class       = className
for         = htmlFor
tabindex    = tabIndex

- Should return only one Tag, but we can manage it with this:-
<>
</>

- Render JavaScript varibales in {var}

- node_modules Folder should be in .gitignore
We can resolve it using package.json and package.lock.json

- The HTML Tags which are not having Closing Tags should be seld-close with < .. />
- "#" in href Attribute should be replaced with "/"
- Add Bootstrap CDN Links of css / js in index.html in src

- Use npm run build while deploy on Production

- We can create custom Components in src Folder
- Name if the Component should ne Always start with Capital Letter
- Use props to pass dynamic content to the Component

VS Code Settings:-
Search with emmet and add new item as follows:-
item: javascript value: javascriptreact

- Use JavaScript Variable in {varName} in JSX

- Component Name should have First Letter CAP always
- In Component:-
  	import React from 'react'
  	export default function(props){
  	  	return(
  	  		<div>{props.title}</div>
  	  	);
  }
- Import Component before Use in App.js:-
  <Navbar></Navbar> OR <Navbar title="TextUtils" />

- propTypes:-
import PropTypes from 'prop-types'

function HelloWorldComponent({ name }) {
  return (
    <div>Hello, {name}</div>
  )
}

HelloWorldComponent.propTypes = {
  name: PropTypes.string
}

export default HelloWorldComponent

- Specifies the default values for props:
Greeting.defaultProps = {
  name: 'Stranger'
};

- We can make any Prop as required with:-
HelloWorldComponent.propTypes = {
  name: PropTypes.string.isRequired
}

- React Router Dom
npm install react-router-dom

- "npm run build" will create "Build" Folder which we need to Deploy on Server

- Deploy using GitHub Pages:-
Search GitHub Pages on https://create-react-app.dev/docs/deployment/ and follow the Steps.
