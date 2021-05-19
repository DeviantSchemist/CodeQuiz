# CodeQuiz
This is a coding quiz that the user takes to test their knowledge of various coding concepts. Utilizing the Bootstrap framework, buttons are clickable and each user's score is saved at the end of the quiz by entering their initials. Each user has 60 seconds overall to do the quiz and each incorrect answer subtracts 10 seconds from their current time. The quiz is over when the timer reaches 0 or the full amount of questions is answered.

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