# Quiz-game
The quiz game project is a simple interactive application developed using the Tkinter library in Python. The project aims to provide a quiz for users with different difficulty levels: Easy, Medium, and Hard. The user can select their desired difficulty level and then proceed to answer a series of multiple-choice questions.

Here's how the quiz game works:

1. The user is presented with a graphical user interface (GUI) window with a title "Technical Quiz" and a "Select Difficulty Level" section containing a dropdown menu to choose the difficulty level (Easy, Medium, or Hard).

2. When the user clicks the "Start Quiz" button, the selected difficulty level is recorded, and the quiz frame is displayed.

3. The quiz frame shows the current question, a timer (set to 60 seconds), and four options represented by radiobuttons. The user can select one of the options by clicking the respective radiobutton.

4. Once the quiz starts, the timer begins to count down from 60 seconds. If the user does not answer a question within the time limit, a message box appears, indicating that time is up, and the next question is displayed automatically.

5. After answering each question, the user clicks the "Next" button, and the selected answer is checked against the correct answer. The result is recorded, and the next question is displayed until all the questions are answered.

6. When all the questions are answered, a message box appears with the user's quiz result, showing the number of correct and incorrect answers, the percentage of correct answers, and a personalized performance message based on the user's score.

7. The user also has the option to restart the quiz by clicking the "Restart" button, which takes them back to the difficulty selection screen.

The quiz game provides an interactive way for users to test their technical knowledge across various difficulty levels. The application's functionality is built upon functions that handle question display, timer management, answer validation, and result presentation. The code uses Tkinter for the GUI components and data structures to organize the questions, options, and correct answers based on difficulty levels.
