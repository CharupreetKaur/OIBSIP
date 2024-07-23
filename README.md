This repository consists of servlet, jsp, html and css files for creating a Number Guessing Game. The game allows users to guess a randomly generated number between 1 and 100.
The user can select different difficulty levels, and the game tracks the user's attempts and high scores. 
1. GuessingGameServlet.java
This servlet handles the core logic of the game:
a) It initializes a random number if it doesn't exist in the session.
b) It processes the user's guess and updates the number of attempts.
c) Depending on the user's input, it provides feedback (too low, too high, correct guess).
d) It handles the game reset and difficulty levels.

2. game.jsp
This JSP file is the main game interface where users can input their guesses. It displays:
a) A form for the user to enter their guess.
b) Feedback messages based on the guess.
c) The number of attempts and high score.

3. indexB.html
This HTML file is similar to indexA.jsp but intended for a different initial page. It provides:
a) An input field for the user to select the difficulty level before starting the game.
b) A form to submit the user's guess.
c) Displays a message and high score (defaulted to 0).

4. indexA.jsp
This JSP file serves as the initial game setup page where users can select the difficulty level before starting the game. It initializes:
a)An input field for selecting the difficulty level.
b)A form to start the game and submit guesses.

5. end.jsp
This JSP file is displayed when the game ends, either by correctly guessing the number or running out of attempts. It shows:
a)A message indicating the outcome.
b)The user's score for the current game.
c)The high score.
d)A button to restart the game.

6. style.css
This CSS file defines the styling for the application. It includes:
a) General styling for the body, headers, and main sections.
b) Specific styles for elements such as buttons, input fields, and messages.
c) A retro game aesthetic using the "Press Start 2P" font.
