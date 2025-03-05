# Self-Driving Car Simulation

This project simulates a self-driving car using JavaScript and HTML5 Canvas. The car is controlled by a neural network that can be trained to navigate a road with traffic.

## Features

- Simulates multiple cars with AI control
- Visualizes the neural network's decision-making process
- Allows saving and loading the best-performing neural network
- Adjustable number of cars and mutation rate

## Project Structure

- `index.html`: The main HTML file that sets up the canvas elements and includes the scripts.
- `style.css`: The CSS file for styling the page.
- `main.js`: The main JavaScript file that initializes the simulation and handles the animation loop.
- `car.js`: Defines the `Car` class, which represents the self-driving car.
- `controls.js`: Defines the `Controls` class, which handles user input for controlling the car.
- `road.js`: Defines the `Road` class, which represents the road and its lanes.
- `sensor.js`: Defines the `Sensor` class, which simulates the car's sensors.
- `network.js`: Defines the `NeuralNetwork` and `Level` classes, which represent the neural network and its layers.
- `utils.js`: Contains utility functions for linear interpolation and polygon intersection detection.
- `visualizer.js`: Contains functions for visualizing the neural network.

## Getting Started

To run the simulation, simply open `index.html` in a web browser.

### Controls

- Use the arrow keys to control the car manually.
- Click the save button (💾) to save the best-performing neural network to local storage.
- Click the discard button (🗑️) to remove the saved neural network from local storage.

### Customization

You can customize the simulation by modifying the following parameters in `main.js`:

- `const N = 1000;`: The number of cars in the simulation.
- `NeuralNetwork.mutate(cars[i].brain, 0.1);`: The mutation rate for the neural network.

## License

This project is licensed under the MIT License.