# codequiztwo

What I did:
Created the HTML and CSS pages
For the Javascript:
I first gathered all HTML elements for manipulation
Then created the quiz questions object + other global variables
The first function cycles through the object array containing the quiz questions to generate the questions + answers
The second function is starting the quiz function, starts the time ranges, hides the start button and displays the 1st quiz question
Then I created the timer
The third function is the end page screen that displays your score after you complete the quiz or if the timer runs out
Once you click the submit button, we run the function high score that saves and stringifies the array of high scores already saved in local storage as well as pushing the new user name + score into the array we are saving in local storage
Then it runs the function to show high scores 
The fourth function clears the list for the highscores and generates a new high score list from local storage
The fifth function displays the high scores page while hiding all of the other pages
The sixth function clears the local storage of the high scores as well as clearing the text from the high score board
The seventh function sets all the variables back to their origional values and shows the home page to allow re-play of the quiz
The eigth function checks the response to each answer
And at the bottom there is the button that will actually start the quiz :) 

# 04 Web APIs: Code Quiz

As you proceed in your career as a web developer, you will probably be asked to complete a coding assessment, which is typically a combination of multiple-choice questions and interactive challenges. Build a timed code quiz with multiple-choice questions. This app will run in the browser and feature dynamically updated HTML and CSS powered by your JavaScript code. It will also feature a clean and polished user interface and be responsive, ensuring that it adapts to multiple screen sizes.

## User Story

```
AS A coding bootcamp student
I WANT to take a timed quiz on JavaScript fundamentals that stores high scores
SO THAT I can gauge my progress compared to my peers
```

## Acceptance Criteria

```
GIVEN I am taking a code quiz
WHEN I click the start button
THEN a timer starts and I am presented with a question
WHEN I answer a question
THEN I am presented with another question
WHEN I answer a question incorrectly
THEN time is subtracted from the clock
WHEN all questions are answered or the timer reaches 0
THEN the game is over
WHEN the game is over
THEN I can save my initials and score
```

The following animation demonstrates the application functionality:

![code quiz](./Assets/04-web-apis-homework-demo.gif)

### Review

You are required to submit the following for review:

* The URL of the functional, deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
