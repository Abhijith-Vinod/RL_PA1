# DA6400: Reinforcement Learning - Programming Assignment #1

## Environments

This project implements and evaluates reinforcement learning algorithms on the following Gymnasium environments:

1. **CartPole-v1**: Balance a pole on a moving cart.
2. **MountainCar-v0**: Drive a car up a mountain using strategic accelerations.

## Algorithms

We implement and compare:

- SARSA with ε-greedy exploration
- Q-Learning with Softmax exploration

## Key Features

- Hyperparameter tuning using wandb
- Evaluation across 5 random seeds for robustness
- Comparative analysis of SARSA and Q-Learning
- Reward shaping (where necessary)

## Repository Structure

- `cartpole.ipynb`: Implementation for CartPole-v1
- `mountaincar.ipynb`: Implementation for MountainCar-v0
- `requirements.txt`: Dependencies
- `README.md`: This file

## Results

For each environment, we provide:

- Learning curves (episodic return vs episode number)
- Variance analysis across 5 random seeds
- Top 3 best hyperparameter configurations

## How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Run Jupyter notebooks:
  jupyter notebook cartpole.ipynb
  jupyter notebook mountaincar.ipynb

## Contributors

- Abhijith Vinod : EP20B002
- Shuhaib Ali : EP20B037

## Academic Integrity

This project adheres to the academic code of conduct. All sources are properly cited.


