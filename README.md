# Handwritten Digit Recognition Using Decision Trees

## Project Overview

This project uses supervised machine learning to recognize handwritten digits (0–9) using decision tree classifiers. The goal is to explore how varying the depth of a decision tree affects prediction accuracy, classification error, and overfitting.

## Dataset

The project uses the handwritten digits dataset provided by scikit-learn.

- 1,797 handwritten digit images
- Each image is represented by an 8×8 pixel grid (64 features).
- Pixel intensity values range from 0 to 16.
- Each image is labeled with its corresponding digit (0–9).

## Implementation

- Visualized handwritten digits and their corresponding pixel intensity values.
- Trained decision tree classifiers with varying maximum depths.
- Analyzed how increasing tree depth affects classification error.
- Compared training and testing error rates to identify overfitting.
- Split the dataset into 80% training data and 20% testing data.
- Generated predictions on previously unseen handwritten digit images.
- Visualized predictions alongside actual digit labels, highlighting correct and incorrect classifications.

## Results

The final decision tree model, trained with a maximum depth of 10, achieved **81.11% accuracy** on the testing dataset.

The project demonstrated that increasing decision tree depth improves training accuracy but can lead to overfitting, reducing the model's ability to accurately classify unseen data.

## Technologies Used

- Python
- Jupyter Notebook
- scikit-learn
- NumPy
- Pandas
- Matplotlib

## Key Concepts

- Supervised Learning
- Decision Tree Classification
- Model Training and Testing
- Overfitting
- Classification Error
- Model Complexity and Generalization
