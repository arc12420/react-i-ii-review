### Remember

Answer these on your own, then compare answers as a group

1.  What is React? Javascript library used to manage the DOM.

2.  What is create-react-app? How you create a new app within your computer

3.  What is Component Based Architecture? A system of containing items within other items and organizing them within there designated box

4.  What is JSX? Basically the baby of JS and HTML (reacts version of html)

5.  What is the virtual DOM? lightweight copy of the DOM

6.  What is unidirectional (one-way) data flow? means that data can only flow one way.

### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app` it creates the location where your new app will be stored within your computer

8.  Summarize the steps for forking and cloning a repo with an existing React app. How does this process differ from the process of creating a new React app on your laptop? You open in github, fork the repository, clone it. You paste the clone url into your terminal. Your terminal should be within the file where you want to store the files. After cloning you need to install react to the file using npm install. After it has installed you enter npm start to open your npm window within your browser.

9.  Explain what this code does:

```jsx
import React from "react";

const Mentor = props => (
  <div className="mentor-container">
    <h1 className={props.title === "Lead Mentor" ? "lead" : ""}>Tim Biles</h1>
    <ul>
      <li>Fort Worth, TX</li>
      <li>My email address is timbilestimbiles@gmail.com</li>
    </ul>
  </div>
);

export default Mentor;
```

10.  Explain how data is passed from a parent component to a child component.

### Apply

Try these on your own, but work together if you start to get stuck.

11.  Use `create-react-app` to create a new React application called `student-directory`

12.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

13. What are the benefits and drawbacks of using a tool like create-react-app?

14. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

15. Compare and contrast one-way data flow with two-way data binding.
