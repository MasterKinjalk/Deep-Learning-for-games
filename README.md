# Deep-Learning-for-games

This is my Plagroud for learnign DQN based RL.

# CartPole Reinforcement Learning

This repository contains Python code for training a reinforcement learning agent using Q-learning to solve the CartPole problem in the Gym environment.

## Overview

- Discretizes the continuous state space of the CartPole environment.
- Applies Q-learning with epsilon-greedy exploration.
- Logs learning rates, exploration rates, and episode-related statistics.

## Prerequisites

- [Python](https://www.python.org/) (3.x recommended)
- [Gym](https://gym.openai.com/) library
- [NumPy](https://numpy.org/) library
- [Matplotlib](https://matplotlib.org/) library

## Usage

1. Clone this repository.
2. Install the required dependencies.
3. Run the code to train the agent.
4. Visualize the results and training progress.

## Results

- Monitor the time per episode and average time per episode.
- Observe learning rates and exploration rates.
- Visualize the training progress.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by OpenAI's Gym environment.
- References to Q-learning and reinforcement learning concepts.


# Pendulum Environment for OpenAI Gym

The Pendulum environment is an implementation of the classic inverted pendulum swingup problem for reinforcement learning, available as a custom environment in OpenAI Gym.

## Description

The Pendulum environment consists of a pendulum attached at one end to a fixed point, and the other end being free. The goal is to apply torque on the free end to swing the pendulum into an upright position, with its center of gravity right above the fixed point.

### Key Features

- Continuous action space for applying torque.
- Observation space includes angular coordinates and velocity.
- Customizable parameters such as gravity, mass, and length.

## Action Space

The action is a continuous torque applied to the pendulum, with limits:

- Min: -2.0
- Max: 2.0

## Observation Space

The observation includes the x-y coordinates of the pendulum's free end and its angular velocity:

- x: cos(theta), normalized between -1.0 and 1.0
- y: sin(theta), normalized between -1.0 and 1.0
- Angular Velocity: -8.0 to 8.0

## Reward Function

The reward is calculated based on the pendulum's angle and dynamics:

- Minimum Reward: -16.2736044
- Maximum Reward: 0

## Getting Started

You can use the Pendulum environment to train and evaluate reinforcement learning agents. See the example code in this repository for a demonstration.

## Installation

You can install this environment as part of the OpenAI Gym package.

## Usage

Follow the Gym API to create and interact with the Pendulum environment. An example code is provided in this repository.

## Version History

- v1: Simplified math equations, no behavior difference.
- v0: Initial release.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Enjoy experimenting with the Pendulum environment for reinforcement learning!
