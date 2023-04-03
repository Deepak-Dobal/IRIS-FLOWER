# IRIS-FLOWER

# Machine Learning Project : Iris-flower-classification
**This program applies basic machine learning (classification) concepts on Fisher's Iris Data to predict the species of a new sample of Iris flower.**

#Software and Libraries

**Python 3.6.0
Anaconda 4.3.0 (32 bit)
scikit-learn 0.18.1
Introduction**

The dataset for this project originates from the UCI Machine Learning Repository. The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis.

**The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor).
Four features were measured from each sample (in centimetres):
Length of the sepals
Width of the sepals
Length of the petals
Width of the petals
Working of the iris_decision_tree_classifier**

**The program takes data from the load_iris() function available in sklearn module.
The program then creates a decision tree based on the dataset for classification.
The user is then asked to enter the four parameters of his sample and prediction about the species of the flower is printed to the user.
Working of the iris_selfmade_KNN**

**The program takes data from the load_iris() function available in sklearn module.
The program then divides the dataset into training and testing samples in 80:20 ratio randomly using train_test_learn() function available in sklearn module.
The training sample space is used to train the program and predictions are made on the testing sample space.
Accuracy score is then calculated by comparing with the correct results of the training dataset.**

**In the given scenario, four different machine learning models, Logistic Regression, Decision Tree, Random Forest, and Support Vector Machines (SVM), were trained and evaluated on the Iris flower dataset. The accuracy of each model is reported as follows:**

**Logistic Regression: 97.0% Decision Tree: 97.0% Random Forest: 97.0% SVM: 97.0% The Iris flower dataset is a well-known and relatively small dataset, with only four input features and three target classes. Achieving high accuracy on this dataset is relatively easy for most machine learning algorithms, but the relative performance of different algorithms on this dataset can still provide useful insights into their strengths and weaknesses.**

**In this case, we can see that all four models achieved the same high accuracy on the Iris dataset, which suggests that they are all capable of learning the underlying patterns in the dataset and making accurate predictions. However, it's important to note that accuracy alone does not provide a complete picture of a model's performance, and it's necessary to evaluate other metrics such as precision, recall, and F1-score to better understand a model's strengths and weaknesses.**
