# IRIS Flower prediction using Tensorflow
Today I want you to show how you can use the **Tensorflow** to train **Iris Dataset**, a model that can categorize data.
## IRIS Dataset
This is probably the most versatile, easy and resourceful data set in pattern recognition literature. Nothing could be simpler than iris data set to learn classification techniques. If you are totally new to data science, this is your start line. The data has only 150 rows & 4 columns.
The data set contains 50 records of 3 species of Iris:
- Iris virginica 
- Iris setosa
- Iris versicolor
<img style="float: center;" width = 500px; src="http://python.astrotech.io/_images/iris-flowers.png"/>

Each records contains 4 features:

Sepal length
Sepal width
Petal length
Petal width
and each record has a species (class) assigned.


# API Description
## tf.contrib.learn
TensorFlow’s high-level machine learning API (tf.contrib.learn) makes it easy to configure, train, and evaluate a variety of machine learning models. In this tutorial, we’ll use **tf.contrib.learn** to construct a neural network classifier and train it on the **Iris data set** to predict flower species based on sepal/petal geometry.

# Steps
We'll write code to perform the following five steps:
1. Load CSVs containing Iris training/test data into a TensorFlow Dataset
2. Construct a neural network classifier
3. Fit the model using the training data
4. Evaluate the accuracy of the model
5. Classify new samples

