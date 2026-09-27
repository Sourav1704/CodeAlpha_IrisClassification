# Iris Flower Classification 🌸

This project is part of my **CodeAlpha Data Science Internship**.

In this project, I built a machine learning model that predicts the species of an Iris flower using its sepal and petal measurements.

The three species are:

- Setosa
- Versicolor
- Virginica

## What I Did

I worked through the project step by step:

- Loaded the Iris dataset using Scikit-learn
- Explored the dataset using Pandas
- Checked for missing values and duplicate records
- Removed duplicate data
- Performed exploratory data analysis (EDA)
- Created visualizations to understand the data
- Split the data into training and testing sets
- Trained different classification models
- Evaluated the models using accuracy, precision, recall and F1-score
- Created a confusion matrix
- Tested the model with a new flower sample

## Dataset

I used the built-in Iris dataset available in Scikit-learn.

It contains four measurements for each flower:

- Sepal length
- Sepal width
- Petal length
- Petal width

The target is the Iris species.

The dataset was loaded using:

```python
from sklearn.datasets import load_iris

The original dataset contained 150 records. During data cleaning, one duplicate record was removed, leaving 149 unique records for the analysis.
Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
Machine Learning Models
I trained and compared two classification models.
Logistic Regression
Test accuracy: 96.67%
Decision Tree
Test accuracy: 93.33%
The Logistic Regression model correctly classified 29 out of 30 test samples.
Model Evaluation
I used the following methods to evaluate the models:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
The Logistic Regression model achieved 96.67% accuracy on the test dataset.

Project Structure :
CodeAlpha_IrisClassification/
│
├── Iris_Classification.ipynb
├── README.md
├── requirements.txt
└── .gitignore

How to Run

First, clone the repository:
git clone YOUR_GITHUB_REPOSITORY_URL

Move into the project folder:
cd CodeAlpha_IrisClassification

Create a virtual environment:
python3 -m venv .venv

Activate it:
source .venv/bin/activate

Install the required libraries:
pip install -r requirements.txt

Then open the Jupyter Notebook:
Iris_Classification.ipynb

Run the notebook cells from top to bottom.


What I Learned
Through this project, I got practical experience with data cleaning, exploratory data analysis, data visualization, classification algorithms and model evaluation.
It also helped me understand how a machine learning model can use data to make predictions.
Internship
CodeAlpha Data Science Internship
Author
Sourav Kumar

