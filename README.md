# Multilayer Perceptron (MLP) Neural Network from Scratch

## 🚀 About the Project
This repository contains the practical implementation of a Multilayer Perceptron (MLP) Neural Network developed within the Google Colab environment. The main objective of this project is to demonstrate the internal mechanics of supervised learning, moving beyond standard "black-box" libraries to focus closely on hyperparameter tuning, layer architecture, and weight convergence.

## 🧠 Technical Details and Algorithm
The model is structured to process input data through a hidden layer and generate predictions at the output layer.
* **Optimization Algorithm:** Backpropagation for dynamic weight adjustments via gradient descent.
* **Activation Functions:** Application of the Hyperbolic Tangent ($tanh$) function and its respective derivative for error propagation and calculation across hidden layers.
* **Evaluation Metrics:** The script assesses learning efficiency by generating comprehensive reports including:
  * Confusion Matrix
  * Accuracy (achieving a high score of 97% in tests performed)
  * Precision and Recall
  * ROC Curve and Area Under the Curve (AUC) calculation

## 🛠️ Technologies Used
* **Python** (Google Colab Environment)
* **Numpy** (For matrix computation and linear algebra)
* **Matplotlib / Seaborn** (For plotting the ROC Curve and Confusion Matrix)

## 📊 How to Run the Project
1. Clone this repository or download the `.ipynb` file.
2. Open the file directly in [Google Colab](https://colab.research.google.com/).
3. Execute the cells in sequence to visualize the training process and the graphical validation metrics.
