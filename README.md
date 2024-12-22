# Neural Network Implementation in TensorFlow

This project is a comprehensive guide to implementing a neural network using TensorFlow, including forward propagation, backpropagation, and gradient descent. The project is designed to provide a deeper understanding of the foundational concepts of neural networks and their implementation.

---

## Features

- **Forward Propagation:**
  - Single neuron implementation with custom weights and biases.
  - Multi-layer and multi-neuron network forward pass.
  - Matrix-based computation for scalability.

- **Backpropagation and Gradient Descent:**
  - Loss function calculation using Mean Squared Error (MSE).
  - Random weight initialization and gradient updates.
  - Gradient computation with TensorFlow's `GradientTape`.

- **Training Process:**
  - Iterative training with parameter updates.
  - Demonstration of weight and bias adjustments to minimize loss.

---

## Workflow

1. **Data Preprocessing:**
   - Housing dataset is imported and scaled using `StandardScaler`.
   - Target variable (price) is log-transformed for normalization.

2. **Forward Propagation:**
   - Single-layer, single-neuron implementation with sigmoid activation.
   - Multi-layer, multi-neuron forward pass using TensorFlow operations.

3. **Loss Calculation:**
   - Compute the difference between predicted and actual values.
   - Calculate loss using the MSE formula.

4. **Backpropagation:**
   - Compute gradients of weights and biases with respect to loss.
   - Update parameters using gradient descent.

5. **Training:**
   - Iterative forward and backward passes to minimize loss.
   - Random weight initialization and gradient visualization.

---

## Requirements

- Python 3.x
- TensorFlow 2.x
- Pandas
- NumPy
- scikit-learn

Install the required libraries using:

```bash
pip install tensorflow pandas numpy scikit-learn
