# Neural Network Implementation in TensorFlow with Keras

This project is a comprehensive guide to implementing a neural network using TensorFlow and demonstrates the flexibility of Keras for building and training deep learning models. It includes forward propagation, backpropagation, and gradient descent to showcase the foundational concepts of neural networks.

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

- **Integration with Keras:**
  - Option to use Keras layers (`tf.keras.layers.Dense`) for defining network architectures.
  - Leverage Keras for flexible and modular neural network design.

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
   - Multi-layer, multi-neuron forward pass using TensorFlow operations and Keras layers.

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
- Keras (included with TensorFlow)
- Pandas
- NumPy
- scikit-learn

Install the required libraries using:

```bash
pip install tensorflow pandas numpy scikit-learn
