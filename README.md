# Handwritten Digits Recognition - ANN 🧠✍️

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📌 Overview
This project demonstrates how to build and train an **Artificial Neural Network (ANN)** to recognize handwritten digits. Using the famous **MNIST dataset**, the model takes images of handwritten numbers (0-9) as input and predicts the correct digit with high accuracy.

This repository serves as an introduction to Deep Learning concepts, specifically Feed Forward Neural Networks (Dense Layers).

## 📂 Dataset
* **Name:** MNIST (Modified National Institute of Standards and Technology) database.
* **Content:** 60,000 training images and 10,000 testing images.
* **Format:** 28x28 pixel grayscale images.

## 🛠️ Technologies Used
* **Python:** Core programming language.
* **TensorFlow / Keras:** For building and training the neural network.
* **NumPy:** For matrix operations and data handling.
* **Matplotlib:** For visualizing the data and training performance (loss/accuracy graphs).
* **Scikit-Learn:** (Optional) For confusion matrix and classification reports.

## 🏗️ Model Architecture
The model uses a simple Multi-Layer Perceptron (MLP) architecture:
1.  **Input Layer:** Flatten layer to convert 28x28 images into a 1D array (784 neurons).
2.  **Hidden Layers:** Dense layers with ReLU activation to learn patterns.
3.  **Output Layer:** A Dense layer with 10 neurons (one for each digit 0-9) using **Softmax** activation for probability distribution.

## 🚀 How to Run locally

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Hanifullah313/Hands_Written_Digits-Recognition-ANN.git](https://github.com/Hanifullah313/Hands_Written_Digits-Recognition-ANN.git)
    cd Hands_Written_Digits-Recognition-ANN
    ```

2.  **Install dependencies:**
    ```bash
    pip install tensorflow numpy matplotlib notebook
    ```

3.  **Run the Notebook:**
    Launch Jupyter Notebook or Jupyter Lab to view the training process.
    ```bash
    jupyter notebook
    ```

## 📊 Results
* **Training Accuracy:** ~98% 
* **Test Accuracy:** ~97% 
## 🤝 Contributing
Contributions, issues, and feature requests are welcome!

## 📝 License
This project is open source and available under the [MIT License](LICENSE).
