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

### Methodology

##### 1. Exploratory Data Analysis (EDA)
- Analyzed player ratings, victory conditions, and opening strategies.
- Visualized correlations between features like player ratings and outcomes.

##### 2. Monte Carlo Tree Search (MCTS)
- Simulated potential game outcomes to select the most promising moves.

##### 3. Deep Reinforcement Learning (DRL)
- Trained a custom chess environment using the PPO algorithm.
- Evaluated the model's ability to predict actions and optimize strategies.

### Results

##### EDA Insights:
- The majority of games end in checkmate or resignation.
- Certain openings, like the Slav Defense, are more successful for specific player ratings.

##### Reinforcement Learning:
- The agent learned basic strategies but exhibited challenges in long-term planning.
- Future iterations may improve performance with enhanced state representations and reward functions.

### Source

https://www.kaggle.com/datasets/datasnaek/chess
