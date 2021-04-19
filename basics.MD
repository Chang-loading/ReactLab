JSX >> extension to javascript
needs babel to translate it to browser understandable format;

it would scan through the script and looking up Markup syntax such as <p> </p> 
then would call createElement(...)

const pE1 = <p>Hello React </p> 
is the same as 
const pE1 = React.createElement("p" {}, "Hello React");

#1: React皆组件 - Component
```javascript
// Example - Button component:
function Button (props) {
  // Returns a DOM element here. For example:
  return <button type="submit">{props.label}</button>;
}

// To render the Button component to the browser
ReactDOM.render(<Button label="Save" />, mountNode)
```