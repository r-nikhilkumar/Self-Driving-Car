# Self-Driving Car Simulation (Python)
This project simulates a self-driving car navigating a virtual environment using the power of deep learning and a user-friendly interface.

### Prerequisites
- Python 3.x (https://www.python.org/downloads/)
- pip (package installer for Python - usually comes bundled with Python)

### Installation
- Open your terminal or command prompt.

- Run the following commands to install the required libraries:

```Bash
pip install torch
pip install kivy
```
Use code with caution.
content_copy
Project Structure
```ai.py```: This file houses the core of the simulation - the neural network architecture and training code for the self-driving car.
```map.py```: This file handles the user interface (UI) creation, car movement logic, and obstacle detection.
Running the Simulation
## 1. Train the Neural Network (```ai.py```):

- Open ai.py in a preferred text editor or IDE.
- You can customize hyperparameters and training data within this file (if needed).
- Run ```ai.py``` from your terminal. This will train the neural network, preparing it for the simulation.
## 2. Start the Simulation (```map.py```):

- Open ```map.py``` in a text editor or IDE.
- You can further customize the UI elements within ```map.py``` to personalize your experience (optional).
- Run ```map.py``` from your terminal. This will launch the UI window showcasing the self-driving car in action.

- ### User Interaction
- The car will initially explore the environment with random movements.
- To create obstacles, simply click and drag your mouse on the background of the UI window.
- Observe how the trained neural network guides the car to navigate around the obstacles you create.

- ### Further Development Ideas
- Experiment with different neural network architectures and training data in ai.py to improve the car's performance and decision-making.
- Enhance the UI in ```map.py``` by adding features like different environments, performance indicators, or even a bird's-eye view.
- Explore incorporating collision detection and avoidance mechanisms to create a more realistic simulation.

- ### Additional Notes
- This is a foundational simulation designed for educational purposes. It might require further development to achieve realistic self-driving car capabilities.
- It's important to be mindful of computational limitations depending on your hardware resources. Training complex neural networks might require powerful GPUs.

- ### Disclaimer
- This project serves as a learning tool for understanding the principles of self-driving cars using deep learning. It's not intended to be a production-ready system for real-world deployment.

## Future Goals
- Integration with Vision AI: Enhance the project by integrating advanced computer vision techniques for lane detection, traffic sign recognition, and pedestrian detection to improve the car's navigation capabilities.
- Reinforcement Learning: Implement reinforcement learning algorithms to allow the car to learn from its environment and improve its driving strategy over time.
- Augmented Reality (AR): Incorporate AR features to create a more interactive and immersive simulation experience, displaying real-time overlays for navigation hints, detected objects, and performance metrics.
- Real-world Data: Utilize real-world driving data to train and test the neural network, increasing the simulation's accuracy and realism.


## Developer details
- Nikhil Kumar
- [Email](thenikhilkumar1@gmail.com)