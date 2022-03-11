# React Basics

## JSX
- Javascript in side HTML requires {}
- When returning HTML, must be all be on tag

## Components
- Divides UI into pieces
- Must start with capital letters
- Remember must use props object
- There are function components and class components
- Class components require render()

## Props
- Example:
```
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}

function App() { 
  return (
    <div className="App">
      <Welcome name="John"/>
      <Welcome name="Mary"/>
      <Welcome name="Alex"/>
    </div>
  );
}
```