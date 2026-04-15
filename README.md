# Artificial Neural Networks for Digits Classification

Machine Learning project exploring handwritten digit classification using Artificial Neural Networks (ANNs).

The project uses the Digits dataset and implements several feedforward neural network architectures to analyse how different hyperparameters influence model performance.

Dataset source:  
https://scikit-learn.org/stable/auto_examples/classification/plot_digits_classification.html


---

# Project Structure

```
ann-digits-classification/
│
├── ann_digits_classification.ipynb
└── README.md
```

---

# Project Overview

The goal of this project is to classify handwritten digits using Artificial Neural Networks (ANNs).

The project explores how neural network architecture and hyperparameter choices affect model performance. Several network configurations are implemented and evaluated in order to compare their classification accuracy.

The workflow includes:

1. Loading the Digits dataset
2. Preprocessing the dataset
3. Designing and training a feedforward neural network
4. Experimenting with different network architectures
5. Evaluating and comparing model performance

---

# Dataset

The **Digits dataset** contains images of handwritten digits from **0 to 9**.

Each image:

- has a size of **8 × 8 pixels**
- is represented as **64 numerical features**
- contains grayscale intensity values

The objective of the model is to correctly classify each image into its corresponding digit.

---

# Data Preprocessing

Before training the neural network, several preprocessing steps are performed:

- **Normalising pixel values** to improve model training
- **Splitting the dataset** into:
  - training set
  - validation set
  - test set

This allows the model to be trained, tuned and evaluated on separate data subsets.

---

# Artificial Neural Network Architecture

The project implements a **feedforward fully connected neural network**.

The baseline architecture includes:

- input layer (64 features)
- one hidden layer
- output layer with 10 neurons (digits 0–9)

The network learns to map pixel values to digit labels through the training process.

---

# Model Experiments

Several additional neural network configurations are created by modifying important hyperparameters.

Examples of modifications include:

- changing the number of neurons in the hidden layer
- adding an additional hidden layer
- modifying activation functions
- adjusting other training parameters

Each model is trained and evaluated to analyse how these design choices influence performance.

---

# Model Evaluation

The performance of each neural network configuration is evaluated using classification accuracy.

The experiments compare:

- baseline ANN model
- modified ANN architectures
- differences in performance across configurations

This allows analysis of how neural network design decisions impact classification results.

---

# Results and Analysis

The experiments demonstrate that:

- neural network architecture strongly affects model performance
- increasing model complexity can improve accuracy, but may also increase training time
- appropriate hyperparameter choices are important for achieving optimal performance

These results highlight the importance of model design and experimentation when working with neural networks.

---

# Technologies Used

- Python  
- NumPy  
- Keras  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

# Running the Project

Install dependencies:

```
pip install numpy matplotlib scikit-learn keras
```

Launch Jupyter Notebook:

```
jupyter notebook
```

Open and run:

```
ann_digits_classification.ipynb
```

---

# Dataset

Digits Dataset (Scikit-learn)

https://scikit-learn.org/stable/auto_examples/classification/plot_digits_classification.html
