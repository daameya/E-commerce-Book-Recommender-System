# E-commerce-Book-Recommender-System
End to End e-commerce book recommendation machine learning application with deployment based on collaborative filtering ML algorithm

# Dataset has been used:

* [Dataset link](https://www.kaggle.com/ra4u12/bookrecommendation)

# Concept used to build the model.pkl file : NearestNeighbors

1 . Load the data
	
2 . Initialise the value of k

3 . For getting the predicted class, iterate from 1 to total number of training data points

4 . Calculate the distance between test data and each row of training data. Here we will use Euclidean distance as our distance metric since it’s the most popular method. 

5 . Sort the calculated distances in ascending order based on distance values
	
6 . Get top k rows from the sorted array

# Built With
1. streamlit
2. Machine learning
3. sklearn

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/daameya/E-commerce-Book-Recommender-System.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
python -m venv books
```

```bash
books\scripts\activate
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```