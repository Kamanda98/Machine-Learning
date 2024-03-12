# Machine-Learning

This repository includes a synthetic dataset designed for a binary classification task, containing 1500 instances. The objective is to demonstrate how a Decision Tree classifier can be used effectively in this context.

The dataset generation process utilizes NumPy and Matplotlib libraries in Python. Class 1 instances are created using three Gaussian distributions centered at [6,14], [10,6], and [14,14] respectively. On the other hand, Class 0 instances are generated with a uniform distribution spanning the range [0, 20].

For the classification task, a Decision Tree classifier is implemented using the scikit-learn library. The dataset is divided into training and testing sets. The classifier is trained on the training set and subsequently evaluated for its accuracy on the test set. This approach serves to demonstrate the effectiveness of Decision Trees in accurately classifying the synthetic data.
