### Remember

Answer these on your own, then compare answers as a group

1.  What is React?

A javascript database 

2.  What is create-react-app?
React is a Boiler-plate that creates a React application that fills in a

3.  What is Component Based Architecture?


4.  What is JSX?

A syntax that allows us to use javascript funcationality in HTML


5.  What is the virtual DOM?
<!-- https://stackoverflow.com/questions/21965738/what-is-virtual-dom -->

6.  What is unidirectional (one-way) data flow?



### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app`

    <!-- 
    1. Creates folders called the 'app-you-created"
    2. creates a git respository
    3.  -->

8.  Summarize the steps for forking and cloning a repo with an existing React app. How does this process differ from the process of creating a new React app on your laptop?

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
