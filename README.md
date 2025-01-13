# Chess-Game-Strategy Optimization with Deep Reinforcement Learning

This project leverages a dataset of over 20,000 online chess games to develop and optimize chess strategies using Monte Carlo Tree Search (MCTS) and Deep Reinforcement Learning (DRL). The dataset, obtained from Lichess.org, includes game outcomes, player ratings, and move sequences, making it ideal for analyzing decision-making and strategy in chess.

### Overview

This project focuses on applying advanced AI techniques to predict optimal moves and strategies in chess games. The key objectives include:

- Using Monte Carlo Tree Search (MCTS) for move prediction.
- Implementing Deep Reinforcement Learning (DRL) to train a chess-playing agent using the PPO algorithm from Stable-Baselines3.
- Analyzing patterns and trends in chess gameplay through exploratory data analysis (EDA).

### Dataset

The dataset contains over 20,000 games collected from Lichess.org using their API. The data includes:

- Game ID: Unique identifier for each game.
- Player Ratings: Ratings for white and black players.
- Move Sequences: Standard chess notation for moves.
- Game Outcomes: Winner, game duration, and victory conditions.
- Openings: Opening names and codes (ECO format).

### Problem Statement

Chess, with its immense decision space and strategic intricacies, provides a perfect environment for training AI. The challenges addressed in this project include:

1. Training AI to evaluate and choose optimal moves in a vast decision tree.
2. Developing strategies using historical game data and reinforcement learning.
3. Analyzing AI's gameplay and decision-making process to identify areas of strength and improvement.

These objectives are pursued with broader implications for game theory, adversarial dynamics, and cooperative problem-solving.

### Solution Approach

##### 1. Exploratory Data Analysis (EDA)
- Analyzed player ratings, victory conditions, and opening strategies.
- Visualized correlations between features like player ratings and outcomes.

##### 2. Monte Carlo Tree Search (MCTS)
- Simulated potential game outcomes to select the most promising moves.

##### 3. Deep Reinforcement Learning (DRL)
- Trained a custom chess environment using the PPO algorithm.
- Evaluated the model's ability to predict actions and optimize strategies.

### Key Findings

MCTS and Decision-Making:
- Effectively simulated game states to identify optimal moves.
- Visualized how exploration and exploitation influenced decision paths.

RL Agent Performance:
- Early stages: Frequent mistakes as the agent explored move possibilities.
- Later stages: Improved strategic play, leveraging learned patterns for intermediate-level gameplay.

Game Insights:
- Player ratings correlate with game duration, suggesting deeper strategies among higher-rated players.
- Draws were more frequent in balanced games with high Elo ratings.

### Future Directions

- Advanced Strategy Development: Extend training to include endgame scenarios and advanced tactics.
- Real-Time Play: Enable the agent to play in live matches against human opponents.
- Multi-Agent Learning: Explore cooperative or competitive play between multiple AI agents.
- Explainability: Incorporate explainability tools like SHAP to better understand the agent’s decision-making.

### Source

https://www.kaggle.com/datasets/datasnaek/chess
