# Fake-News-Detection-Project
Fake news detection using Data Analytics method along  with python language.

The dataset used for this project is news.csv. Dataset has a shape of 7796*4.
The dataset has four columns: first identifies the news, second and third are title and text and the fourth one is the label denoting FAKE or REAL.

Follow the below steps to complete the project:

1. Make the necessary imports.
2. Read the data into the data frame and get the shape of the data.
3. Now get the labels from the DataFrame.
4. Split the dataset into training and testing models.
5. Initialize the TfidfVectorizer with stop words from English and maximum document frequency of 0.7.
6. Initialize the PassiveAggressiveClassifier.
7. At last print the confusion matrix to gain the data about false and true negatives and positives.
8. After completion of the project, we get an accuracy of 92.82%.

Software requirements: Pycharm Community Edition.

Programming Languages and modules: Python3, Numpy-module, pandas, sklearn.
