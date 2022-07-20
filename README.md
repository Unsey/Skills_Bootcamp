# Skills_Bootcamp
#Mini projects from the Edge Hill Skills Bootcamp in Cloud Computing and Data Analytics


# TASK 1
# Your task is to import this dataset using both libraries (Pandas and Sci-Kit Learn) in your tutorial1.py file.
# Using Pandas to read the wine.csv file available on Blackboard and then use Sci-Kit learn to import from its dataset folder.
# You will load them to different variables called dataset and datasetSKL and print their values


# TASK 2

# For this task, you are asked to split the wine dataset into features and labels.
# To do this, you need to separate the column Class from the original dataset because this column represents the dataset label (what you aim to predict or find out).
# Using the same file (tutorial1.py) and dataset (wine.csv), your task is to create a new variable called features and assign to it all the features from the wine dataset,
# which is currently contained in the variable dataset created in Task 1.
# The second step is to create a variable label and assign to it the dataset label (i.e. column Class).
# At the end of this task, you will have two new variables containing the features and label of the wine dataset.

# TASK 3

# For this task, you will have to split the features and label from the wine dataset used in the previous tasks.
# To do that, create 4 variables to store the split portions of the dataset (respectively: X_train, X_test, Y_train, Y_test)
# using the train_test_split function from Sci-Kit Learn in a proportion of 60% for training and 40% for testing. In the end, print their values.


# TASK 4

# For this task, you will have to implement a Decision Tree Classifier and do a prediction using the trained algorithm. To achieve this, follow the steps:
# 1. Import the Decision Tree Classifier and assign it to a variable called d_tree.
# 2. Train this algorithm by calling the function fit with the previously created wine training features (X_train) and training label (Y_train).
# 3. Do a prediction using the function predict and the X_test dataset portion, save this prediction in a variable called Y_pred. Print this prediction on the console.

# TASK 5

# For this task, you will be asked to calculate the accuracy of your model previously developed in the previous tasks and
# then generate a scatter graph comparing prediction values with expected ones.
# To do this, follow the steps:
# 1. Import the function accuracy_score from the Metrics module in the Sci-Kit Learn library.
# 2. Call that function using Y_test and Y_pred variables as input values.
# 3. Print the percentage of the accuracy on the console.
# 4. Import Pyplot module from Matplotlib and use plt as an alias.
# 5. Call the function figure to create a new figure to be displayed on the screen.
# 6. Call the function scatter and use for X and Y respectively the values from Y_test and Y_pred variables.
# 7. Also, add chart labels (e.g. Prediction/Expected) for X and Y using xlabel and ylabel functions.
# 8. Finally, call the function show().

