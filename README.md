# CS 370: Pirate Intelligent Agent

## Project Overview

For this project, I developed a pirate intelligent agent that uses deep Q-learning to navigate an 8x8 maze and find a treasure located in the bottom-right corner. The starter code provided the maze environment in `TreasureMaze.py`, the experience replay system in `GameExperience.py`, and the neural network model in the Jupyter Notebook. I was responsible for completing the Q-training algorithm in the notebook.

I created the training process that allows the pirate to learn through exploration and exploitation. The agent stores its experiences in replay memory and uses those experiences to improve the neural network's Q-values. I also used a target network to help make the training more stable. After training, the agent reached a 100% win rate and passed the completion check, showing that it could successfully navigate the maze and find the treasure.

## What Do Computer Scientists Do and Why Does It Matter?

Computer scientists solve problems using programming, algorithms, data, and computational methods. Their work matters because computer systems are used in many areas of everyday life, including communication, entertainment, finance, healthcare, and business. This project showed me that computer science is not just about writing code. It also involves understanding a problem, choosing an appropriate solution, testing it, and making improvements when necessary.

## How Do I Approach a Problem as a Computer Scientist?

I approach problems by breaking them into smaller parts and understanding how the different components work together. I start by looking at the requirements and reviewing the code or tools that are already available before deciding what needs to be created or changed. In this project, I needed to understand how the maze environment, experience replay, neural network, and Q-learning algorithm worked together before completing the training function. I also use testing to make sure that my solution actually works instead of assuming that code is correct just because it runs without errors.

## What Are My Ethical Responsibilities to the End User and the Organization?

Computer scientists have a responsibility to consider how the systems they create affect the people who use them. This includes protecting user information, reducing harmful bias, testing systems for reliability, and being honest about the limitations of a technology. Developers also have a responsibility to their organization by creating secure, maintainable, and reliable software. As AI systems become more capable, I think it is especially important for developers to consider what a system should be allowed to do, not just what it is technically capable of doing.
