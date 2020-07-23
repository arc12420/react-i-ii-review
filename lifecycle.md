### Remember

Use https://reactjs.org/docs/react-component.html#the-component-lifecycle and http://projects.wojtekmaj.pl/react-lifecycle-methods-diagram/ to answer these on your own then compare answers as a group

1.  Each component has several `lifecycle methods` that you can override to do what? Override to run code at specific times

2.  What are the 4 categories of lifecycle methods? (these are the headings from the first link)  Mounting, unmounting, updating, error handling

3.  What are the names of the 5 commonly used lifecycle methods? (these are in bold in the first link) Constructor, render, component DidMount, componenet did update, shouldComponentUpdate

### Understand

Discuss this question in pairs if you have a 4-person group

4.  What's going on in this code? Consol logging "dwight saved the day"

```jsx
import React, { Component } from "react";

class Mentor extends Component {
  componentDidUpdate() {
    console.log("Dwight saved the day!");
  }
  render() {
    return (
      <div>
        <h1>Dwight Schrute</h1>
        <h2>{this.props.questions.length}</h2>
        <h3>questions to answer</h3>
        <h4>"dwight saved the day!" <h4>
        <button onClick={this.props.answerQuestion}>Answer a question!</button>
      </div>
    );
  }
}
```

### Apply

Try these on your own, but work together if you start to get stuck.

5.  Update the `Mentor` component above so that the message that is currently being console.log'd is displayed below the number of questions to answer instead.
