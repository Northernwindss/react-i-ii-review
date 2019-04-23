### Remember

Answer these on your own, then compare answers as a group

1.  What is React?

  Created by facebook to rule the world secret but not so secretly.
  
  library that helps us interact with the Dom.


2.  What is create-react-app?

  A library that allows us to have access to frameworks and other useless packages

3.  What is Component Based Architecture?

  The idea that when you build a website its a number of different things that all work together to make a functional website

4.  What is JSX?

  Reacts language that incorporates html, javascript, etc

5.  What is the virtual DOM?

  looks at the original file then compares it to the changes made and updates them

6.  What is unidirectional (one-way) data flow?

    Data that just flows from parents to children

### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app`

You create a react app called "my-app" with frameworks and packages thaht allow us to make a website easier

8.  Explain what this code does:
there is a var called mentor that  will check to see if it has the title 'lead mentor' or 'lead', his name is time biles, info accosiated with him is he is from Fort Worth, Tx, and his given email address

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

9.  Explain how data is passed from a parent component to a child component.

  in oroder to pass down from partent to child we need to pass it down by props

### Apply

Try these on your own, but work together if you start to get stuck.

10.  Use `create-react-app` to create a new React application called `student-directory`

11.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

12. What are the benefits and drawbacks of using a tool like create-react-app?

13. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

alot of react

14. Compare and contrast one-way data flow with two-way data binding.

the html automatcially reflex the changes that take place
