# Machine-learning-projects-ScikitLearn

**1. prodict house prices_LinearRegression:** 

prediction using square footage and bedrooms and bathrooms, evaluation with std.Important features:
- Linear Regression model
- OneHotEncoder
- generalization : train_test_split

**2. breast-cancer-m-or-b-Logistic Regression:**

This project aims to predict whether a tumor is malignant (M) or benign (B) based on clinical and histological data. The dataset used for this analysis is the Breast Cancer Dataset, which contains various features extracted from cell nuclei in digital images.Important features:
- Accuracy,Precision,Recall
- Data Preprocessing & StandardScaler
- Logistic Regression model

**3. titanic-survivors-Random Forest:**

Using the data set of the Titanic passengers, we want to predict which of the passengers probably survived and then compare the prediction with the reality.Important features:
- Preprocessing
- Random Forest model
- kaggle competition

**4_breast_cancer_GrideSearch**

In this code for Breast Cancer Dataset , we run the SVM model with two different methods, once with hyperparameter setting and once without setting.
- SVM with cross_validate & GridSearchCV methods
- new generalization : K-fold
- best hayperparameters
- We have three parts of data: validation, training and testing
- Regularization ---> model Lasso(L1) & model Ridge (L2) & hyperparameter C

**5_Dimensionality_reduction**

We use the dataset prepared by scikit_learn about vegetation (covtype) and because the number of columns or features is large, we can use the techniques of reducing their dimensions:
- Principal Component Analysis - PCA
- The most important features using covariance
- The most important features using variance


**6.RecommenderSystem-KNN-movies**

Using the K-Nearest Neighbors (KNN) model, we are going to build a Recommender System. In this dataset, various movies are categorized by genre. New items:
- KNN model and using different K
- Recommender System Structure
- preprocessing


**7.Clustering**

 is similar to classification, but the target or label is not clear.In this code, we examine two common methods for clustering.We also review some common techniques. New items:
- Clustering models ---> K-Means  & DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
- Clustering methods ---> WCSS (Within-Cluster Sum of Squares) & Silhouette 
- make_blobs (for random data)
