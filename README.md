Multi-Layer Perceptron (MLP) 
from Scratch 🧠A pure Python/NumPy implementation of a Neural Network designed to learn a linear relationship ($y = 2x$). 
This project demonstrates the core mechanics of Deep Learning—Forward Propagation, Backpropagation, and Gradient Descent—without relying on high-level frameworks like PyTorch or TensorFlow

📌 OverviewGoal: 
Train a network to predict $y$ given $x$, 
where the target relationship is $y = 2x$.
Input Data: [[1.0], [2.0], [3.0], [4.0]]
Target Labels: [[2.0], [4.0], [6.0], [8.0]]Tech Stack: Python, NumPy.

🏗️ Network Architecture
The model is a 2-Layer Neural Network (1 Hidden Layer).
Layer,Nodes,Shape,Activation,Role
Input,1,"(N, 1)",None,Receives raw input x.
Hidden,3,"(1, 3)",ReLU,Learns internal features from the input.
Output,1,"(3, 1)",Linear,Combines features to predict y^​.
