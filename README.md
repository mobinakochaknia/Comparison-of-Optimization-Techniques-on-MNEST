# Comparison of Optimization Techniques on MNEST

## Overview
This project explores training neural network models using PyTorch and PyTorch Lightning frameworks. The code compares several optimization techniques and visualizes the results of each, allowing for a detailed analysis of their performance based on accuracy and loss metrics.

## Features
- **Custom Model Architectures**: Includes multiple models implemented as PyTorch `nn.Module` or `LightningModule`.
- **Training and Evaluation**: Tracks training progress across epochs and logs accuracy and loss.
- **Data Visualization**: Uses Matplotlib and Seaborn to visualize training metrics and data distributions.
- **Performance Metrics**: Detailed evaluation of models on specified datasets.
- **Optimization Techniques**: Includes comparisons and analyses of optimization algorithms and their variations.

## Optimization Techniques Explored
### Compare Adam and RMSprop
- **Objective**: Analyze the differences in performance, convergence speed, and final accuracy when using Adam and RMSprop optimizers.
- **Observations**: Include insights into how these optimizers handle learning rates and adapt to gradients.

### Impact of Different Learning Rates on SGD
- **Objective**: Demonstrate the impact of varying learning rates on the performance of Stochastic Gradient Descent (SGD).
- **Key Results**: Highlight trends such as underfitting with high learning rates and slow convergence with very low learning rates.

### SGD with Momentum vs. Classic SGD
- **Objective**: Compare the behavior of standard SGD with and without momentum.
- **Findings**: Discuss the benefits of momentum in overcoming local minima and improving convergence speed.

### Mini-Batch Gradient Descent
- **Description**: Implements mini-batch gradient descent for improved computational efficiency and smoother convergence.
- **Insights**: Outline the trade-offs between batch size, stability, and convergence rate.

## Training Details
- **Epochs**: Training conducted over multiple epochs to optimize model performance.
- **Accuracy**: 
  - [Add specific details on training and validation accuracy trends.]
- **Loss**:
  - [Add specific details on training and validation loss trends.]

## Installation Instructions
1. Clone this repository:
   ```bash
   git clone [https://github.com/mobinakochaknia/Comparison-of-Optimization-Techniques-on-MNEST/tree/main]
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook [Comparison of Optimization Technique].ipynb
   ```

## Usage
1. Open the Jupyter Notebook in your preferred IDE.
2. Run cells sequentially to:
   - Load data
   - Train models
   - Evaluate performance
3. Visualize results using the provided plotting functions.

## Dependencies
- Python 3.x
- PyTorch
- PyTorch Lightning
- Matplotlib
- Seaborn
- NumPy
- Pandas

## Contributing
Contributions are welcome! Please fork the repository and create a pull request for any feature additions or improvements.


