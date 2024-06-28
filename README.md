# Stock Trading with Deep Reinforcement Learning

## Overview
This project explores the use of Deep Reinforcement Learning (DRL) to develop and evaluate stock trading strategies. The project is based on cutting-edge research and aims to leverage advanced DRL techniques to optimize trading decisions.

## Objectives
- Implement and compare various DRL agents for stock trading.
- Evaluate the performance based on return, volatility, and Sharpe ratio.
- Include transaction costs in the trading environment for realistic simulations.

## Environment Setup
1. **Install Dependencies**:
    - Install necessary packages such as `gymnasium`, `numpy`, `pandas`, `matplotlib`, and `stable-baselines3`.

2. **Clone the Repository**:
    - Clone the GitHub repository and navigate to the project directory.

## Steps to Run the Project
1. **Prepare the Stock Data**:
    - Ensure your stock data is in a suitable format (e.g., CSV files).
    - Load the data into the environment.

2. **Define the Trading Environment**:
    - Create a custom trading environment (`StockTradingEnv`) that includes transaction costs.
    - Define the observation and action spaces for the environment.

3. **Implement DRL Agents**:
    - Implement various DRL agents using algorithms such as PPO, A2C, DDPG, SAC, TD3.
    - Train the agents on the custom trading environment.

4. **Evaluate the Agents**:
    - Calculate daily returns, standard deviation, and Sharpe ratio for each agent.
    - Compare the performance of the agents based on these metrics.

5. **Plot the Results**:
    - Visualize the performance metrics using bar charts.
    - Highlight the best-performing agents based on the Sharpe ratio.

## Results
- **DDPG Agent** showed the highest return and Sharpe ratio, despite higher volatility.
- **TD3 Agent** and **Ensemble Agent** also performed well, balancing return and risk.
- **PPO Agent** underperformed, indicating the need for further optimization.

## Key Takeaways
- Advanced DRL algorithms like DDPG and TD3 can significantly enhance trading strategies.
- Including transaction costs makes simulations more realistic.
- Continuous improvement and testing are essential for refining these models.

## Research Paper
This project was inspired by the research paper [Deep Reinforcement Learning for AutomatedStock Trading: An Ensemble Strategy](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3690996). The paper provides a comprehensive overview of using DRL in financial markets and guided the development of the agents and environment in this project.
