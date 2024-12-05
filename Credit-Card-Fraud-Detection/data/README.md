### Dataset Download

To access the dataset, click the link below to download it from Kaggle:

[Download the Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download)

### Files in the Dataset

- **creditcard.csv**: The main dataset containing credit card transactions and their features.

### Dataset Overview

The dataset includes transaction details for each credit card purchase, with labels indicating whether a transaction was fraudulent or not. It is used to train a machine learning model to classify future transactions as legitimate or fraudulent.

### How to Use the Data

Once you've downloaded the dataset, you can begin by loading it into your local environment. In Python, you can use pandas to read the CSV file:

```python
import pandas as pd

# Replace with the path to where you've saved the dataset
data = pd.read_csv('path/to/creditcard.csv')
