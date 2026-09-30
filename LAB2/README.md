
### Program Title
Comparison of Gradient Descent Implementations

### Aim
This notebook implements and compares two variants of Gradient Descent – Batch Gradient Descent (BGD) and Stochastic Gradient Descent (SGD) – using both a custom NumPy implementation and a TensorFlow/Keras neural network. The objective is to understand their behavior and performance on a classification task.

### Dataset Used
The `make_moons` dataset from `sklearn.datasets` is used. This is a synthetic 2D binary classification dataset that creates two interleaved half-circles, which is suitable for testing non-linear classifiers.

### Brief Note on Results
Both custom NumPy and Keras implementations were trained for 200 epochs. The results are as follows:

*   **Custom NumPy Implementation:**
    *   Batch Gradient Descent Accuracy: 0.965
    *   Stochastic Gradient Descent Accuracy: 0.9725

*   **Keras Implementation:**
    *   Batch Gradient Descent Accuracy: 0.8650
    *   Stochastic Gradient Descent Accuracy: 0.9700

The custom NumPy SGD implementation achieved the highest accuracy, closely followed by the Keras SGD implementation. The Keras Batch Gradient Descent showed comparatively lower accuracy in this specific setup.
