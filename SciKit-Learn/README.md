# What is SciKet-learn ?
SciKet-learn is one of the most popular python library for Machine Learning and Data Analysis.It is built on top of NumPy, Pandas and Matplotlib etc.This Library is used to build and train machine learning models.It provides simple and efficient tools for analyzing data and creating predictive models.
<br>
In Simple words we can say that
Scikit-learn is a Python library that helps developers and data scientists create machine learning models easily using built-in algorithms and tools.
<br>

<b>Installation:</b>

```bash

pip install SciKet-learn

```

<b>Check it version:</b>

```bash

import sklearn
print(sklearn.__version__)
```

<b>Applications of Scikit-learn:</b>

```bash
1. Recommendation systems

2. Fraud detection

3. Medical diagnosis

4. Image classification

5. Sales prediction

5. Customer analysis

```

# Some Important Modules of SciKet-learn

<b>1. sklearn.datasets :</b> This modules is used to load/import built-in datasets.Also used for generate sample datasets.some example of built-in datasets are Iris dataset, Wine dataset, Digits dataset.

Example:

```bash
from sklearn.datasets import load_iris

iris = load_iris()

```

<b>2. sklearn.model_selection :</b> This module is used for spliting datasets, cross-validation, Hyperparameter tuning.
<br>
Some important function that comes under model_selection module.

```bash
train_test_split() 
cross_val_score()
GridSearchCV

```

Example:

```bash
from sklearn.model_selection import train_test_split

```

<b>3. sklearn.linear_model :</b>  sklearn.linear_model is a module in Scikit-learn that provides linear machine learning algorithms used for Regression, Classification, Regularization.

Example:

```bash
from sklearn.linear_model import LinearRegression

```

# What is Regression Analysis :
Regression analysis is a statistical method in statistics used to examine or predict the relationship between a dependent variable(output) and one or more independent variable(inputs).
with the goal of prediction and understanding how variable influence each other.
Here Dependent variable (Y) means what you want to predict or explain and Independent variable(s) (X) means the predictors or inputs.
<br>
In Simple words we can say that it is the answer of the "if X changes, how will Y change ?"
<br>
Example: predicting house prices based on size, location, and age.


