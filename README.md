# 05 Multilayer Neural Network - Iris Classification

## Overview

This project implements a multilayer neural network (MLP) to classify iris flower species using the Iris dataset. It includes data preprocessing, exploratory data analysis (EDA), feature scaling, model training, hyperparameter optimisation using Bayesian Optimisation (Optuna), and evaluation.

Dataset source:  
https://www.kaggle.com/datasets/uciml/iris

---

## Repository Contents

- Multilayer_NN_Iris.ipynb  
- Iris.csv  
- README.md  

---

## How to Run

1. Download or clone this repository.  

2. Open Google Colab:  
   https://colab.research.google.com  

3. Upload the notebook:  
   **Multilayer_NN_Iris.ipynb**  

4. Upload the dataset file:  
   **Iris.csv**  

5. Run the notebook. When prompted:

   Select optimisation method (GS,BO):

   Type:  
   **bo**

6. Continue running all cells until completion.

---

## Requirements

- pandas  
- numpy  
- matplotlib  
- seaborn  
- tensorflow  
- scikit-learn  
- optuna  

---

## Notes

- The dataset is small and highly separable  
- Feature scaling is applied before training  
- Bayesian Optimisation (TPE sampler) is used with 10 trials  
- Early Stopping is used to prevent overfitting  
- The model achieves near-perfect accuracy  
- Learning rate and number of epochs are the most important hyperparameters  

---

## Authors

- Camila Gonzalez – [GitHub Repo](https://github.com/camilagzzaa/Multilayer_neural_network_with_hyperparameter_optimisation.git)
- Matteo Peroni - [GitHub Repo](https://github.com/perofficial/mlp_hyperparameters_optimisation)
- Mariana Samperio - [Github Repo](https://github.com/mariana-samperio-cuevas/multilayer_nn_hyperparameter_optimisation)
