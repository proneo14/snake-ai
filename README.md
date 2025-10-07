Reinforcement Learning Snake AI

A self-learning Snake game AI built entirely from scratch using reinforcement learning. The project features a custom-coded Snake environment and an agent that learns to play the game through trial and error. After extensive training, the AI achieved an impressive high score of 147, demonstrating strong spatial awareness and long-term reward optimization.

Features
- Custom-built Snake environment (no external game engine)
- Reinforcement Learning agent using Q-learning or Deep Q-learning principles
- Adaptive learning through state–action–reward updates
- Achieved a high score of 147 through self-improvement
- Real-time visualization of the game and agent performance

Tech Stack
- Python
- NumPy, Matplotlib
- Pygame (for visualization)

How It Works
- Environment Setup: The Snake game provides a state space (snake position, direction, and food location) and possible actions (turn left, right, or go straight).
- Agent Training: The agent receives rewards for eating food (+10), penalties for collisions (-10), and small negative rewards to encourage efficient movement.
- Learning Process: The model uses Q-learning or Deep Q-learning to approximate the value of each state-action pair and gradually improve its decision-making.
- Performance: After training over thousands of episodes, the agent learned to avoid collisions, anticipate movement patterns, and maximize its score — achieving 147 points.

Results
- High Score: 147
- Decreasing average penalties across episodes
- Improved reward curve indicating stable learning behavior

Future Improvements
- Implement convolutional layers for visual state inputs
- Integrate experience replay and target networks for improved stability
- Expand environment with varying speeds or grid sizes

  
