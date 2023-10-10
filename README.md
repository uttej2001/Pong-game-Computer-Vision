# Computer Vision Pong Game

This project is a modern twist on the classic Pong game that uses computer vision and hand movements for control. It combines the nostalgic gameplay of Pong with cutting-edge technology to create an immersive and interactive gaming experience.

## How It Works

1. **Camera Initialization**
   - The game utilizes the computer's webcam to capture real-time video.
   - The camera's resolution is set to 1280x720 pixels.

2. **Image Loading**
   - Various images are loaded into the game, including background images, the game over screen, and images for the ball and paddles.

3. **Hand Detection**
   - The game employs the `cvzone` library to detect hands within the webcam feed.
   - It sets a confidence threshold for hand detection and allows for the tracking of multiple hands.

4. **Game Loop**
   - The core of the game is a continuous loop that processes webcam frames and updates the game state.

5. **Game Logic**
   - During each iteration of the game loop, the script performs several crucial tasks:
     - Detects hand positions and distinguishes between left and right hands.
     - Renders paddle graphics on the screen based on hand positions.
     - Handles collision detection between the ball and paddles.
     - Updates the score when the ball successfully hits a paddle.
     - Checks for game-over conditions when the ball goes out of bounds.
     - Displays the game-over screen and final score when the game ends.
     - Allows the player to restart the game by pressing the 'r' key.

6. **Displaying the Game**
   - The game overlays various visual elements on the webcam feed, including the background, paddles, ball, and score display.
   - A small window within the game screen displays the raw webcam feed, providing players with a real-time view of their hand movements.

## Try It Yourself

You can try this unique and interactive Pong game by running the provided Python script on your computer. Follow the on-screen instructions and control the game using your hand movements.

Have fun playing this modernized version of Pong, and challenge your friends to beat your high score!

<img width="960" alt="Screenshot 2022-05-25 122811" src="https://user-images.githubusercontent.com/72940291/170199721-fb825697-ca7c-4a0f-a2b2-178039cab8d4.png">
<img width="960" alt="Screenshot 2022-05-25 123044" src="https://user-images.githubusercontent.com/72940291/170200192-54c3a0d4-b754-4b36-b286-c0ee6bb8b9e5.png">

## Acknowledgments

This project was inspired by the classic Pong game and built using Python, OpenCV, and the `cvzone` library. Special thanks to the developers of these tools for making this project possible.
