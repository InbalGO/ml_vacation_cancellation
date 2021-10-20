# ml_vacation_cancellation

The goal of the following project was to predict the cancellation probability of future vacation orders in a travel business, according to numerous features, given in a data set.  
This project aims to deal with a classic binary classification problem, where a new register would be given a label of "1" if it is predicted to be canceled or a "0" if not. 

General steps performed in the process:

-	Data exploration and visualization in order to observe any unique feature distribution and find any possible features correlations.
-	Preprocessing the train data including feature engineering, outliers removal, handling missing values and categorical features, data scaling and dimensionality reduction.
-	Performing four machine learning algorithms on the train data (KNN, Logistic regression, Random Forest, Neural Network (MLP), while using the validation set to choose the best hyper-parameters that will minimize overfitting and evaluation of the models using K-fold cross validations and ROC and AUC curves.
-	Based on the results, performed a model evaluation, leading to choosing the best model to perform the final prediction on the test data set, that has achieved highest accuracy, in a reasonable time.

The project was conducted using Python in Jupyter notebook with Scikit-Learn, as well as matplotlib, pandas and seaborn.

Code explanation and notation is included within the Jupyter notebook.

