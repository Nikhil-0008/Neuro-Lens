# NeuroLens

NeuroLens is a project I built to make neural networks easier to understand through visual experiments.

When learning about neural networks, it can be difficult to understand what is actually happening during training just by looking at formulas or accuracy values. I wanted to build something where users could change the network structure, train it on different datasets, and see how the model learns through visualizations.

With NeuroLens, you can experiment with different datasets, upload your own data, adjust hidden layers and neurons, choose activation functions, and observe how the decision boundary changes during training. It also includes an AutoTune option that tests different configurations and selects a suitable one based on the results.

## What can you do with it?

- Try built-in datasets such as Circle, XOR, Spiral, Moons, and Clusters.
- Upload your own CSV, TSV, or TXT dataset.
- Select features and labels from your dataset.
- Change the number of hidden layers and neurons.
- Experiment with Tanh, Leaky ReLU, and Sigmoid activation functions.
- Adjust learning rate, batch size, and training speed.
- Watch the decision boundary change as the network learns.
- View training and testing accuracy, loss, and other metrics.
- Use AutoTune to test different network configurations.
- Save experiment results and export the trained model as JSON.

## How it works

The neural network is implemented from scratch using JavaScript. It uses feedforward propagation, backpropagation, and mini-batch gradient descent to train the model.

The frontend handles training and visualizations, while the Python Flask backend provides datasets and stores experiment results.

I also included additional input features such as x², y², xy, sin(3x), and sin(3y) to let the network experiment with different patterns.

## Technologies used

- Python
- Flask
- JavaScript
- HTML
- CSS
- HTML Canvas

## Running locally

1. Clone this repository.
2. Install the required dependency:

```bash
pip install -r requirements.txt
```

3. Run the application:

```bash
python code.py
```

4. Open `http://127.0.0.1:5000` in your browser.

## Project status

NeuroLens is still a work in progress. I built it as a way to experiment with neural networks and make the learning process more visible. There is still room to improve it, and feedback is welcome.
