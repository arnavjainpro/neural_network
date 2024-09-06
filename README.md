# Neural Network

Welcome to the Neural Network project, a simple implementation designed to help users understand the fundamentals of neural networks and their applications. This project consists of a three-layer neural network where each node in the layers has corresponding weights to determine the flow of data.

![Neural Network Structure](https://i.imgur.com/oJlXD2e.png)

## Key Features

- **Three-layer Architecture**
    - The neural network consists of three key layers: input, hidden, and output. Each layer plays a significant role in processing data and making predictions.
- **Customizable Weights and Biases**
    - Users can modify the weights and biases to optimize the performance of the network.
- **Forward and Backward Propagation**
    - The neural network uses both forward propagation for predictions and backward propagation for error correction during training.
- **Activation Functions**
    - Supports various activation functions like ReLU and Sigmoid, allowing for flexible experimentation.

## Installation Process

1. **Clone the repository:**
    ```bash
    git clone https://github.com/arnavjainpro/neural_network.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd neural_network
    ```

3. **Set up the environment:**
    - Ensure you have Python installed. Create a virtual environment and activate it:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

4. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

5. **Run the application:**
    ```bash
    python train.py
    ```

## Usage

1. **Train the Network:**
    - After setting up the environment, run the `train.py` file to start training the neural network on your dataset.

2. **Modify the Dataset:**
    - You can modify the input dataset in the `input_layer.py` file to train the network on different data.

3. **Fine-tune Weights and Biases:**
    - Adjust the weights and biases in the hidden layers to improve the network's performance during training.

## Customization and Development

- **Modify the Code:**
    - The codebase is flexible and easy to customize. You can add more layers, adjust the number of nodes in each layer, or integrate different activation functions.
- **Extend Functionality:**
    - You can extend the neural network by integrating additional features such as dropout layers, batch normalization, or using more complex datasets for testing.

## Credits

- **Developer:** Arnav Jain
- **Technologies Used:** Python, NumPy, Matplotlib
- **Website:** Visit my personal website at [arnavj.me](https://arnavj.me)
