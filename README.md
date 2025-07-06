# 🚴‍♂️ Predicting Bike Sharing Demand with Neural Networks

## 📘 Project Overview

In this project, we build a **feedforward neural network** from scratch to predict **daily bike rental ridership** based on historical usage patterns and environmental conditions. This is an introductory deep learning project designed to give hands-on experience in implementing neural networks and understanding how they learn from data.

You are provided with some starter code and are expected to complete the core implementation of the network.

---

## 🎯 Objective

- Build a neural network using Python and NumPy
- Train the network to predict hourly bike-sharing demand
- Understand how feature scaling, data normalization, and hyperparameter tuning impact model performance

---

## 🛠️ Tools & Libraries

- Python 3
- `numpy` – For numerical operations and matrix computations
- `pandas` – For data manipulation and preprocessing
- `matplotlib` – For visualizing data and model performance

---

## 🧹 Data Preparation

The dataset used in this project is the **Bike Sharing Dataset** from the UCI Machine Learning Repository. It contains hourly data on the number of bikes rented, along with variables such as:

- Weather conditions
- Time of day
- Temperature
- Humidity
- Working day/holiday indicators

Before training the model, the data is preprocessed by:
- Encoding categorical variables
- Scaling continuous variables
- Splitting into training, validation, and test sets

---

## 🧠 Model Architecture

The project involves building a neural network with:
- One input layer (based on the number of features)
- One or more hidden layers (configurable)
- One output neuron (predicting the number of bikes rented)

Training involves:
- Forward propagation
- Backpropagation
- Gradient descent for weight updates

---

## 📈 Model Evaluation

Model performance is tracked using **loss curves** on both training and validation sets. You are encouraged to experiment with:
- Number of hidden units
- Learning rate
- Number of epochs
- Regularization techniques

---

## 🔗 Data Source

The dataset can be found [here on UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset).

---

## 👤 Contact

**Waqar Ahmed**  
📧 Email: waqar.nu@gmail.com  
🔗 GitHub: [waqar-ahmed91](https://github.com/waqar-ahmed91)

---

## 📜 License

This project is for educational and learning purposes only.
