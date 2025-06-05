# Task-7-Support-Vector-Machines-SVM-

This task is broken down into 5 steps , i will be explaining what i did in each step below

# STEP 1 - Load and prepare a dataset for binary classification
1. I imported libraries needed like scikit learn, matplotlib, pandas , numpy
2. I loaded the dataset using pandas and assigned the name bcancer to it
3. I performed preprocessing and normalization of the data(converted diagnosis categorical values to numerical values)
4. Dropped unecessary values
5. I selected the features and target variables
6. Standardized the values using standard scaler
7. Split the data into train and test sets

# STEP 2 - Training the SVM with linear and RBF kernel
1. Using SVC module i fit the train data into both kernel types RBF and linear
2. Printed the accuracies of both 

# STEP 3 - Visualizing decision boundaries using 2d features
1.  I selected two features from the breast cancer dataset: 'radius_mean' and 'texture_mean', and stored them in a variable X_vis. These two features will be used for visualization.
2. I also extracted the target labels ('diagnosis') into a variable called y_vis.
3. I created a meshgrid, predicted class labels, and plotted the decision boundary with the data points

# STEP 4 - Hyperparameter Tuning
1. imported GridSearchCV module from sklearn
2. Created parameter grid and used the GridSearchCV function and fitted data
3. Printed values of the best parameter found

# STEP 5 - Cross-validation Evaluation
1. Imported cross_val_score, StratifiedKFold modules
2. Used the functions and printed the values
