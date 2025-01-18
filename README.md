# Neural Network Training and Comparison Framework

This repository contains implementations and scripts for training, testing, and evaluating neural networks with a focus on:

1. **Multilayer Perceptron (MLP)**: Implementations include both single-layer and deep MLP architectures.
2. **Comparative Analysis**: Comparing the performance of shallow and deep neural networks on various datasets.
3. **Dataset Preprocessing**: Includes custom preprocessing for datasets such as MNIST and face recognition datasets.
4. **Optimization Techniques**: Utilizes optimization libraries such as SciPy's `minimize` function for training.

## Features

- **Dataset Handling**: 
  - MNIST: Standardized preprocessing and normalization.
  - Custom face dataset: Preprocessed for optimal training efficiency.
- **Custom Weight Initialization**: Provides flexible initialization strategies for neural network weights.
- **Customizable Parameters**: Configure input size, hidden layers, number of classes, and regularization parameters.
- **Performance Evaluation**: Outputs training, validation, and test accuracy for each model.

## Files and Structure

- **`facennScript.py`**: Implementation comparing shallow and deep MLPs on a face recognition dataset.
- **`nnScript.py`**: Script for training neural networks on the MNIST dataset with preprocessing and optimization.
- **`cnn2.ipynb` / `deepnn.ipynb`**: Jupyter notebooks demonstrating CNN and deep learning architectures for exploratory analysis.
- **`mnist_all.mat`** and **`face_all.pickle`**: Data files used for training and validation.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-url.git
   ```
2. Ensure the required dependencies are installed:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the scripts:
   ```bash
   python facennScript.py
   python nnScript.py
   ```
4. Explore the Jupyter notebooks for deeper insights.

## Future Work

- Extend support for additional datasets.
- Implement more advanced neural network architectures.
- Optimize training and evaluation for speed and scalability.
