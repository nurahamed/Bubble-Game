# Bubble-Game

This game, developed using HTML, JavaScript DOM Manipulation, and CSS, offers an engaging and simple browser-based experience. Here's a breakdown of its key features for your GitHub readme.md file:

1. **Score Mechanism:**
   - The player's score starts at 0 and increases by 10 each time they successfully click on the bubble corresponding to the current Hit number.
   
2. **Hit Number Dynamics:**
   - Upon successful clicks, a new Hit number is generated, providing a dynamic and challenging gameplay experience.

3. **Timer Countdown:**
   - The game operates on a timer that counts down from 20 to 0 seconds. This adds a time-sensitive element to the gameplay, increasing excitement and urgency.

4. **Game Over Display:**
   - When the timer reaches 0, the game ends, and the player's final score is prominently displayed. This provides closure to the gaming session.

5. **Wrong Bubble Interaction:**
   - If the player clicks on a bubble that does not match the Hit number, the game also concludes, displaying the current score. Despite this, players are encouraged to try again with a simple click on the "Play again" text.

6. **Replay Option:**
   - Players have the opportunity to replay the game by clicking on the "Play again" text. This seamless restart enhances user engagement and encourages repeated plays.

7. **Technological Stack:**
   - The game leverages HTML for structuring, JavaScript DOM Manipulation for interactivity, and CSS for styling, showcasing a combination of fundamental web development technologies.

8. **Customization and Contribution:**
   - Developers can explore customization options, such as modifying game dynamics, adding levels, or improving the user interface. The readme provides information on running the game, customizing features, and contributing to its development.

Overall, this project serves as an excellent starting point for beginners and offers potential for expansion and enhancement.
The game initializes with a score of 0 and a timer set to 20 seconds. The `getScore()` function increments the score by 10 each time the player successfully clicks on the correct bubble. The `getNewHit()` function generates a random number (the target) and updates the corresponding HTML element to display this target.

The `makeBubble()` function dynamically creates a grid of bubbles, each containing a random number. The grid is initially rendered, and subsequent calls to this function refresh the bubble layout.

The `runTimer()` function initiates a countdown timer that decrements every second. When the timer reaches zero, the game concludes. If a player clicks on the correct bubble, the score increases, a new target is generated, and the timer resets to 20 seconds. Otherwise, if the player clicks on the incorrect bubble, the timer is immediately set to zero.

Upon game over, the final score is displayed along with a message, and an option to play again is provided.

This code is suitable for a beginner-level project and can serve as a foundation for expanding the game's features, such as adding levels, incorporating sound effects, or improving the user interface. The GitHub readme.md file can be enhanced with information on how to run the game, customize features, and contribute to its development.
