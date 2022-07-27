# Jr Dev React Challenge - Quibble

## Specification
Create a functional component that accepts as a prop an array of question objects and renders a quiz. The quiz displays one question at a time in the order that they appear in the questions array, and it only advances to the next question when the user selects an answer choice. The quiz does not support returning to previously answered questions, although you can attempt to add this functionality later. After the user has answered all the questions, display the user’s score as a percentage. An example input array is given below, but be sure not to assume that there are a fixed number of questions or that each question has a fixed number of answer choices. The “correct” field of each question object indicates the index of the correct answer choice in the answers array.


```javascript
const QUESTIONS = [
  {
    question: "What is 2*(4+4)?",
    answers: ["2", "4", "8", "16"],
    correct: 3,
  },
  {
    question: "What is 9*9?",
    answers: ["18", "81", "80", "79"],
    correct: 1,
  },
  {
    question: "Who was the first president of the United States?",
    answers: [
      "George Washington",
      "John Adams",
      "John Quincy Adams",
      "Thomas Jefferson",
    ],
    correct: 0,
  },
  {
    question: "What state is Philadelphia in?",
    answers: [
      "Commonwealth of Pennsylvania",
      "New Jersey",
      "New York",
      "Massachusetts",
    ],
    correct: 0,
  },
  {
    question: "What are the two major political parties in the United States?",
    answers: [
      "Democratic Party & Republican Party",
      "Green Party & Red Party",
      "Bull Party & Moose Party",
      "Hamilton Party & Burr Party",
    ],
    correct: 0,
  },
];
```

## Starter Code
Use the environment you are most comfortable with. I recommend using create-react-app to create a local version of the project so that you can inspect easily from your browser when debugging. Alternatively, you can work from a blank React template in CodeSandbox. Here is some code to get you started: 

```javascript
import React, { useState } from "react";

const QUESTIONS = [...];

function App() {
  return <Quiz questions={QUESTIONS} />;
}

const Quiz = ({ questions }) => {
  // YOUR CODE HERE
};

export default App;
```
**“Questions”** is omitted but is defined as it is in the above specification. You should also try adding new questions and questions with more than 4 answer choices when testing.
