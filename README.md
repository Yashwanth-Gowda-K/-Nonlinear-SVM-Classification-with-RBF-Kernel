This project demonstrates the implementation of Nonlinear Support Vector Machine (SVM) Classification using the Radial Basis Function (RBF) kernel. The model is trained on a synthetic "moons" dataset, which represents a classic example of non-linearly separable data.

📌 Key Features
Uses scikit-learn's SVC with RBF kernel

Demonstrates kernel trick for nonlinear separation

Visualizes decision boundaries for clear understanding

Includes model evaluation via accuracy score

📁 Dataset
Generated using make_moons() from sklearn.datasets

Contains two interleaving half circles with added noise for realism

🧠 Core Concepts
Nonlinear SVM: Maps data into higher-dimensional space using a kernel

RBF Kernel: Allows flexible separation by computing similarity based on distance

Hyperparameters:

C: Controls margin hardness

gamma: Controls influence of individual training points

📈 Output
Model accuracy printed on test data

A plot showcasing the nonlinear decision boundary learned by the SVM
