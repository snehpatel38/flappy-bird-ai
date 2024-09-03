# 🕹️ Flappy Bird AI Evolution

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![NEAT-Python](https://img.shields.io/badge/NEAT-Python-orange?logo=python&logoColor=white)
![Pygame](https://img.shields.io/badge/Pygame-2.0-green?logo=pygame&logoColor=white)

This project is a Python-based implementation of the Flappy Bird game, enhanced with AI using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm. The AI learns to play the game by evolving neural networks over time, adapting to increasingly difficult levels.

## 🔧 Features

- **AI-Powered Gameplay**: The game uses the NEAT algorithm to evolve neural networks that control the bird, learning to avoid obstacles and survive longer.
- **Neural Evolution**: The AI's performance improves over generations through mutation and crossover, simulating natural evolution.
- **Custom Configurations**: The NEAT algorithm's parameters, such as population size, mutation rates, and fitness criteria, are adjustable to experiment with different AI behaviors.

## 🧠 Technologies Used

- **Python**: Core programming language for game development and AI implementation.
- **NEAT-Python**: A Python implementation of the NEAT algorithm used to train the neural networks.
- **Pygame**: Library used to create the game environment.

## 🌐 Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/snehpatel03/flappy-bird-ai
   cd flappy-bird-ai
2. **Install Dependencies**:
   Ensure you have Python installed. Then, install the required Python packages:
    ```bash
    pip install neat-python pygame
3. **Run the Game**:
   Start the game with:
   ```bash
   
   python flappy_bird.py

## 🚀 How It Works
- The game initializes a population of neural networks, each controlling a bird.
- Each bird attempts to navigate through the pipes, and its performance is evaluated based on how far it gets.
- The best-performing networks are selected to reproduce, creating a new generation of birds with slight variations (mutations) from the previous generation.
- Over many generations, the AI improves, learning strategies to survive longer.
