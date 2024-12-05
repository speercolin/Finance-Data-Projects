### `src/` Folder Overview

The `src/` folder contains the Jupyter Notebook file that walks through the entire project, including data analysis, feature selection, model building, evaluation, and result interpretation. It is the main script for understanding the implementation and workflow of the project.

### Contents

- `credit_card_fraud_detection.ipynb`: This Jupyter Notebook is the primary script that:
  1. Loads the dataset.
  2. Performs exploratory data analysis (EDA).
  3. Prepares the data for model training.
  4. Trains the RandomForestClassifier model on the training data.
  5. Evaluates the model using various metrics (e.g., ROC-AUC score, confusion matrix).
  6. Visualizes key results such as feature importance and model performance.

### How to Use the Notebook

1. Ensure you have the `data/` folder with the dataset in place (downloadable from Kaggle).
2. Install the required libraries by running `pip install -r requirements.txt`.
3. Open the `credit_card_fraud_detection.ipynb` notebook in Jupyter and run through each cell to see the code and explanations.
4. The notebook will guide you through the steps of analyzing and building the fraud detection model.

### Project Workflow in the Notebook

The notebook covers the following key stages of the project:

- **Data Exploration**: Understand the dataset's structure, missing values, and feature relationships.
- **Data Preprocessing**: Split the dataset into training, validation, and test sets, and handle any necessary preprocessing steps.
- **Model Training**: Build and train a RandomForestClassifier model.
- **Evaluation**: Evaluate the model's performance using metrics like ROC-AUC and confusion matrix.
- **Feature Importance**: Visualize which features contributed the most to the model's predictions.

By running the Jupyter Notebook, you will gain insights into each step of the machine learning pipeline used to solve the fraud detection problem.

### Requirements

Make sure to have all the dependencies installed by using:

```bash
pip install -r requirements.txt
