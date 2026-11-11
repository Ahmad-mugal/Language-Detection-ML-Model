# Language Detection ML Model

A Jupyter notebook that detects the language of a text sample with machine learning.

## How it works

* Loads a text dataset with a Text column and a language column
* Checks for missing values
* Uses CountVectorizer to turn text into features
* Trains a MultinomialNB classifier from scikit-learn
* Splits the data into training and test sets with train_test_split

## Dataset

22 languages, with 1000 sentences in each language. The notebook reads the dataset from the public Aman Kharwal Website-data dataset.

## Run it

Open Language_Detection.ipynb in Jupyter Notebook or JupyterLab and run the cells in order.

## Tech

Python, pandas, NumPy, scikit-learn, Jupyter Notebook
