# Nepal Earthquake Damage Grade Modeling
## By Shehzad Ali, Dongxuan Zhang, Mu-An Shen, Aatheep Gurubaran, and Sam Worley

In 2015, the capital of Nepal experienced a 7.8 magnitude earthquake. The earthquake took the lives of many, destroyed thousands of buildings, and caused an estimated damage of $10 billion USD. Through multiple models, we are able to predict the damage grade of 72.8% of Nepal buildings and extract important features that helped determine building damage grade. Using our work we put together a plan detailing how our work can be used to mitigate damage from future earthquakes.

## Data 

The data used for this project came from an ongoing drivendata.com competition and was very extensive in both the number of records (number of buildings) and number of attributes for each building containing 260,606 records and 38 columns.

## Models

### Regression
File name: AML_Regression

This file contains the following 8 types of regression models. 
- Simple Linear Regression
- Lasso Regression
- Ridge Regression
- Elastic Net Regression
- Ordinal Regression with the following different link functions:
    - logit
    - Probit
    - Exponential
    - Complementary Log Log

### Decision Trees and Random Forest 
File name: AML_Project_RF_Trees

We tested trees at different depth and ran random forest models with different number of trees to achieve the highest accuracy. These models also extracted the important features for predicting damage grade. 

### Neural Network, Boosting, and PCA
File name: AML_NeuralNetwork_PCA_Boosting

This file contains code for many neural networks, boosting(CatBoost & XGBoost), and PCA combined with neural networks. We achieved our highest accuracy in this file. Neural networks models were used for regression and classification. 

### KNN
File name: AML_KNN_Kmeans

In this file we worked on knn models and k-means clustering. To find the optimal number of neighbors we ran a for loop using a different number of neighbors. 

### Naive-Bayes
File name: AML_NaiveBayes

This file contains the code for our naive-bayes model. This model did not work well so we excluded it from our presentation, but we wanted to make it available so you can see our work/thought process. 
