# CA04 – Ensemble Models
This project involves building various ensemble models to predict income based on demographic variables in a census dataset. The dataset contains 48,842 instances and 7 attributes, with two target classes - >50K and <=50K.

### Data Source and Contents
The dataset is obtained from the Census Bureau and can be accessed using the following link: https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true. The dataset contains a column indicating the rows to be used as training and testing data, and the same data cleaning and transformations done in CA03 can be reused here.

### Finding Optimal Value of a Key Ensemble Method Hyperparameter
One of the key hyperparameters for ensemble models is the number of estimators. This project involves finding the best value for this hyperparameter by plotting the following line graphs:

### Accuracy vs. n_estimators
AUC vs. n_estimators
Building Ensemble Models
The following ensemble models were built for this project:

### Random Forest
AdaBoost
Gradient Boost
XGB
For each model, a graph of Accuracy vs. n_estimators and AUC vs. n_estimators was plotted to determine the optimal number of estimators within the given range.

#### Performance Comparison
For the best values of Accuracy and AUC for each model, a comparison was made to determine the best performing model.

### Deliverables
The following files are included in this project:

A fully functional Jupyter Notebook containing the code for building and evaluating the ensemble models
The dataset used for the project
A README file explaining the project and its contents.
