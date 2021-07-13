# Chess-ai

## About the project
This is a python application that implements a Chess AI. There is also an interface available to against the AI via Jupyter Notebook.

[SCREENSHOT]

## Installation
Clone this repo to your desktop and run `pip install -r requirements.txt` to install the dependencies.

You might want to look into `interface.ipynb` to make change the port you want to use.

## Usage
After you clone this repo to your desktop, go to its root directory and run `jupyter notebook` to open interface.ipynb. Run the cells in the notebook to set up the web app locally. You will then be able to access it at the specified port.

## Features
This Chess AI is powered by the following algorithms:
1. Minimax with Alpha-Beta Pruning
2. Monte Carlo Tree Search with UCB Selection Policy

As a next step, I hope to incorporate deep reinforcement learning into the Chess AI and obtain an elo level to measure performance over iterations.
