# Titanic-Survival-EDA
The Titanic Survival Problem is a well-known data science challenge that involves predicting which passengers aboard the Titanic survived the ship's sinking in 1912. The goal of the problem is to build a model that can accurately predict whether a given passenger would have survived based on a number of features, such as their age, gender, and passenger class. 

In this project more than modelling we will emphasize on the EDA part. We will be creating the ML models. We’ll use different algorithms and find the algorithm with the best accuracy. 

Let’s discuss about the EDA part first and why EDA is useful:

Exploratory Data Analysis (EDA) is an important step in the data science process that involves visualizing and summarizing a dataset in order to better understand its characteristics and identify any patterns or trends. EDA is especially important when working on the Titanic Survival Problem, as it can help us gain insight into the factors that may have influenced a passenger's likelihood of survival.

There are many different techniques that can be used for EDA, and the specific approach will depend on the nature of the data and the questions being asked. Some common EDA techniques for the Titanic Survival Problem might include:

Univariate analysis: This involves examining each feature individually to understand its distribution and any patterns or trends. For example, we might look at the distribution of passenger ages to see if there are any outliers or anomalies.
Bivariate analysis: This involves examining the relationship between two features. For example, we might look at the relationship between passenger class and survival rate to see if higher class passengers had a higher likelihood of survival.
Multivariate analysis: This involves examining the relationship between three or more features. For example, we might look at the relationship between age, gender, and survival rate to see if any specific combinations of these features had a particularly strong influence on survival.
By performing EDA on the Titanic passenger data, we can gain a better understanding of the characteristics of the passengers and how they may have affected their chances of survival. This information can then be used to inform the development of a machine learning model that can accurately predict which passengers survived the sinking. 

In this project we will be plotting a correlation matrix to find out the relationship between different features. 

The main libraries that we will be using for EDA is NumPy, Seaborn, Matplotlib

 

ML Model

Now coming to the modelling part of the project. We will be using different machine learning algorithms to predict the survival of a person. 

Pre-processing the data before applying machine learning algorithms is an important step that can help improve the performance of your model. Some additional details about common pre-processing techniques include:

Handling missing values: NULL or missing values in your dataset can cause problems when training machine learning models, as many algorithms are unable to handle NULL values. There are several approaches you can take to deal with missing values, such as dropping rows or columns with missing values, imputing missing values with the mean or median of the feature, or predicting missing values using a separate model. Which approach you choose will depend on the specific characteristics of your dataset and the goals of your analysis.
Feature selection: Identifying the most relevant features in your dataset and selecting a subset to use in your model can help reduce the complexity of the model and improve its performance. There are several approaches you can take to select features, such as using statistical tests to identify the most important features, using domain knowledge to identify relevant features, or using machine learning algorithms that have built-in feature selection methods.
Feature engineering: Creating new features from existing features in your dataset can help capture additional information or trends in the data that might not be apparent in the raw features. This can be done through techniques such as combining or transforming existing features, or using domain knowledge to create features based on your understanding of the problem.
After Preprocessing the data, we can move on to splitting it into a training set and a test set. This is an important step because it allows us to evaluate the performance of your model on unseen data, which is a more realistic representation of how the model will perform in practice.

After splitting the data, it is often a good idea to perform feature scaling. This is a technique that adjusts the values of numeric features so that they have a common scale. This is important because many machine learning algorithms assume that the features are in the same scale, and failing to perform feature scaling can lead to poor model performance.

Once the data is ready, we can then apply a variety of machine learning algorithms to it and compare their performance. There are many different algorithms to choose from, and the specific algorithm that works best will depend on the nature of the data and the prediction task. Some common algorithms for the Titanic Survival Problem include:

Logistic Regression
Decision Trees
Random Forests
Support Vector Machines
K-Nearest Neighbors
After training and evaluating each algorithm, we can then compare their performance to see which one provides the most accurate predictions. To do this, we can use metrics like accuracy. These metrics will give you an idea of how well the model is able to correctly predict the survival of passengers. 
