# Proj_10_DTC_Purchase_Dataset

## Project Introduction

This project works on a dataset using Decision Tree Classifier (DTC) to predict whether a person will buy a new car or not. The dataset uses features like user's age and estimated salary.

## Purpose

The main purpose of this project is to predict with the help of a machine learning Decision Tree Classifier model whether a user will buy a new car (1 = Yes, 0 = No). This model is based on two main features – age and estimated salary.

## Key Features

- **Dataset Processing:** Dataset with 400 entries including userId, gender, age, estimated salary, and purchased history.
- **Model Training:** Building the model using DecisionTreeClassifier.
- **Model Evaluation:** Evaluating model performance using Confusion Matrix and Accuracy Score.
- **Visualization:** Graphical display of Decision Tree and Confusion Matrix.
- **Features:**  
  - Prediction based on age and salary  
  - Text representation and graphical visualization of the Decision Tree

## How to Use

 **Install Required Libraries:**
   - pandas
   - scikit-learn
   - graphviz

   To install these, run in terminal:
   
   pip install pandas scikit-learn graphviz
   ```

 **Prepare Dataset:**
   The dataset should be named `Purchase_Logistic.csv` and placed in the project folder.

 **Run the Code:**
   Run the project file `Proj_10_DTC_Purchase_Dataset.py`:
   
   python Proj_10_DTC_Purchase_Dataset.py
   ```

4. **See Output:**
   - You will get text and graphical display of the Decision Tree.
   - Confusion Matrix and Accuracy Score will be printed.
   - Decision Tree graph will also be shown (using graphviz).
