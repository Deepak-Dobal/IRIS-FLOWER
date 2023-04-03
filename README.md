# IRIS-FLOWER

# Machine Learning Project : Iris-flower-classification
**This program applies basic machine learning (classification) concepts on Fisher's Iris Data to predict the species of a new sample of Iris flower.**

#Software and Libraries

Python 3.6.0

Anaconda 4.3.0 (32 bit)

scikit-learn 0.18.1

Introduction**

The dataset for this project originates from the UCI Machine Learning Repository. The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis.

![68747470733a2f2f6d69726f2e6d656469756d2e636f6d2f6d61782f3837352f312a37626e4c4b73436858713934516a744169526e3430772e706e67](https://user-images.githubusercontent.com/121633990/229589458-2e1f1b5b-37b5-4ba7-8f62-2e1d8b7e60ca.png)


The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor).
Four features were measured from each sample (in centimetres):

1-Length of the sepals

2-Width of the sepals

3-Length of the petals

4-Width of the petals

# Steps Followed

1-The program takes data from the load_iris() function available in sklearn module.

2-The program then divides the dataset into training and testing samples in 80:20 ratio randomly using train_test_learn() function available in sklearn module.

3-The training sample space is used to train the program and predictions are made on the testing sample space.

4-Accuracy score is then calculated by comparing with the correct results of the training dataset.

5-In the given scenario, four different machine learning models, Logistic Regression, Decision Tree, Random Forest, and Support Vector Machines (SVM), were trained and evaluated on the Iris flower dataset.


# The accuracy of each model is reported as follows
Logistic Regression: 97.0% 
Decision Tree: 97.0% 
Random Forest: 97.0% 
SVM: 97.0% 

The Iris flower dataset is a well-known and relatively small dataset, with only four input features and three target classes. Achieving high accuracy on this dataset is relatively easy for most machine learning algorithms, but the relative performance of different algorithms on this dataset can still provide useful insights into their strengths and weaknesses.**

**In this case, we can see that all four models achieved the same high accuracy on the Iris dataset, which suggests that they are all capable of learning the underlying patterns in the dataset and making accurate predictions. However, it's important to note that accuracy alone does not provide a complete picture of a model's performance, and it's necessary to evaluate other metrics such as precision, recall, and F1-score to better understand a model's strengths and weaknesses.**
