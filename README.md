# ANN_fashion-mnist-Pytorch

# Fashion MNIST Classification using ANN

This project implements an Artificial Neural Network (ANN) to classify images from the Fashion MNIST dataset. The model successfully achieves an accuracy of 89% on the test set.

 Project Overview
The goal of this project is to build a deep learning model that can categorize 70,000 grayscale images (28x28 pixels) into 10 categories of clothing and accessories (e.g., T-shirts, Trousers, Sneakers).

 Model Architecture
The model is a Sequential Artificial Neural Network built with Pytorch. The architecture consists of:
Input Layer: Flattens the 28x28 pixel images into a 1D array of 784 pixels.
  Hidden Layers:  Dense layer with ReLU activation.
    
Output Layer: Dense layer with 10 nodes and Softmax activation for multi-class classification.

 Results
Training Accuracy: ~91%
Test Accuracy: 89%
Loss Function:  Crossentropy Loss
Optimizer: SGD

 How to Run
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open `fashion_mnist_ann.ipynb` in Jupyter Notebook or VS Code and run all cells.

 Tech Stack
* Python
* Pytorch
* NumPy & Pandas
* Matplotlib (for visualization)
