# Penguin Species Classifier using Feedforward Neural Network (ANN)

This project demonstrates a **forward neural network (ANN)** model built using **TensorFlow** to classify penguin species based on their body measurements. The model was trained and evaluated using the **Palmer Penguins Dataset**, a real-world alternative to the classic Iris dataset.



##  Project Overview

| Type          | Multi-class Classification                                |
|---------------|-----------------------------------------------------------|
| Target Labels | Penguin Species (`Adelie`, `Chinstrap`, `Gentoo`)         |
| Features Used | Culmen Length, Culmen Depth, Flipper Length, Body Mass    |
| Model         | Feedforward Neural Network (ANN)                          |
| Activation    | ReLU (hidden layers), Softmax (output)                    |
| Loss Function | Categorical Crossentropy                                  |
| Optimizer     | Adam                                                      |
| Framework     | TensorFlow/Keras                                          |



##  Objective

To classify penguins into one of three species based on their physical characteristics using an **artificial neural network**. The project involves:
- Data cleaning and preprocessing
- Feature scaling and label encoding
- Building and training a neural network
- Evaluating model accuracy
- Visualizing accuracy and loss curves


##  Dataset Description

- **Dataset**: Palmer Penguins
- **Source**: [Kaggle](https://www.kaggle.com/datasets/parulpandey/palmer-archipelago-antarctica-penguin-data)
- **Samples**: ~340 (after cleaning)
- **Features Used**:
  - `Culmen Length (mm)`
  - `Culmen Depth (mm)`
  - `Flipper Length (mm)`
  - `Body Mass (g)`
- **Target**: `Species` (Label-encoded + one-hot encoded)


##  Model Architecture


Input Layer (4 features)
            ↓
Dense Layer (10 neurons, ReLU)
            ↓
Dense Layer (8 neurons, ReLU)
            ↓
Output Layer (3 neurons, Softmax)
