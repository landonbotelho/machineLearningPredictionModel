# Handwritten Digit Recognition Using Decision Trees

## Project Overview

This project uses supervised machine learning to recognize handwritten digits (0–9) using decision tree classifiers. The goal is to explore how varying the depth of a decision tree affects prediction accuracy, classification error, and overfitting.

## Dataset

The project uses the handwritten digits dataset provided by scikit-learn.

- 1,797 handwritten digit images
- Each image is represented by an 8×8 pixel grid (64 features).
- Pixel intensity values range from 0 to 16.
- Each image is labeled with its corresponding digit (0–9).

<img width="730" height="793" alt="image" src="https://github.com/user-attachments/assets/d37b69bf-bcf5-49ba-8bbb-cbc0acb432e6" />


## Implementation

- Visualized handwritten digits and their corresponding pixel intensity values.
- Trained decision tree classifiers with varying maximum depths.
      <img width="1018" height="613" alt="image" src="https://github.com/user-attachments/assets/eebbd880-9931-43aa-b3a7-bced97ac5dea" />
      <img width="1145" height="863" alt="image" src="https://github.com/user-attachments/assets/b6d2f858-0cdc-4127-823a-a216df10bfb6" />
- Analyzed how increasing tree depth affects classification error.
- Compared training and testing error rates to identify overfitting.
      <img width="649" height="700" alt="image" src="https://github.com/user-attachments/assets/10d5ffe2-f78c-4395-b632-61b9648e61cf" />
- Split the dataset into 80% training data and 20% testing data.
- Generated predictions on previously unseen handwritten digit images.
- Visualized predictions alongside actual digit labels, highlighting correct and incorrect classifications.
    <img width="1099" height="984" alt="image" src="https://github.com/user-attachments/assets/2c377495-fc54-4e34-8bac-c59b9b7a289d" />


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
