# Flappy-bird-AI
Flappy bird clone game 
Overview:
In this project, the primary focus is on implementing the core gameplay mechanics of the Flappy Bird game, encompassing the creation of the game character, generation of pipes, handling user input for controlling the bird's flight, managing collisions with pipes, and updating the score. Additionally, this milestone also involves the integration of advanced features such as machine learning-based score prediction and the development of an automated version of Flappy Bird using artificial intelligence.
 
Project Documentation Summary:

 Implemented Gameplay Mechanics:
1. Creating the Bird:
   - Loaded the bird image, defined initial position and velocity.
   - Implemented gravity for falling motion.
   - Allowed user control through key presses (e.g., spacebar) for bird's flight.

2. Generating Pipes:
   - Loaded pipe image, defined gap between pipes.
   - Implemented logic to generate pipes at regular intervals and move them.
   - Randomized pipe heights for gameplay variability.

3. Handling User Input:
   - Listened for user input events like key presses.
   - Responded to key presses to control bird's flight (e.g., jumping).

4. Collision Detection:
   - Implemented collision detection between bird and pipes.
   - Handled game over conditions upon collision.

5. Updating the Score:
   - Tracked player's score based on navigating pipes.
   - Displayed score on screen for player feedback.

Additional Work:
- Machine Learning Model for Score Prediction: 
- Developed a model using Random Forest Regression to predict score based on player's    past playing data. The Playing data exports to CSV. 
- Achieved close to maximum accuracy.

- Automated Version with FNN Neural Network:
 - Created an automated version of Flappy Bird using Reinforcement learning and Feedforward Neural Network (FNN).
 - The AI plays Flappy Bird autonomously for 3 generations, and achieve any score wanted.

Key Decisions and Challenges:
- Key decisions include choosing appropriate algorithms for collision detection, score tracking, and machine learning model for Prediction for Target variable.
- Challenges involve fine-tuning parameters for user control responsiveness, optimizing pipe generation for smooth gameplay, physics equations used for logic for bird movement. Training Feed Forward Neural network model and configuration with multiple bird clones.
