# Self-Driving Car with Neural Network

This project is a simulation of a self-driving car powered by a simple neural network, built from scratch using pure JavaScript without any external libraries.

## Features

- **Neural Network from Scratch**: Implements a basic neural network with mutation capabilities for learning.
- **Sensors**: The car is equipped with sensors to detect its surroundings and road boundaries.
- **Virtual Environment**: A procedural road with lanes and traffic (dummy cars).
- **Genetic Algorithm**: The simulation can evolve multiple cars to find the "best brain" that navigates the traffic most effectively.
- **Visualization**: A built-in visualizer for the neural network's architecture and weights.

## How it Works

1.  **Car Control**: Each AI-controlled car uses its sensor readings as input to its neural network.
2.  **Learning**: The "best brain" (the car that travels furthest) can be saved to `localStorage`. Subsequent simulations will use this brain as a base, applying mutations to optimize performance.
3.  **Visualizer**: The right side of the screen shows the neural network in real-time, highlighting active neurons and connection weights.

## Controls

- **Save Brain**: Saves the neural network of the current best-performing car.
- **Discard Brain**: Deletes the saved neural network.

## Files

- `index.html`: Main entry point and canvas setup.
- `main.js`: Core simulation loop and car generation logic.
- `car.js`: Car physics and rendering.
- `sensor.js`: Ray-casting sensor implementation.
- `road.js`: Road and lane generation.
- `network.js`: Neural network logic.
- `visualizer.js`: Visualization of the neural network.
- `utils.js`: Helper functions (mathematical and geometric utilities).
- `style.css`: Basic styling for the canvas layout.

## Setup

Simply open `index.html` in any modern web browser to run the simulation.
