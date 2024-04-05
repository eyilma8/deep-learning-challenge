# deep-learning-challenge
Module 21 challenge
The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

The purpose of this analysis is 

The goal of this project is to create an algorithm using machine learning and neural networks to predict whether applicants will be successful if funded by the fictional non-profit foundation, Alphabet Soup.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

PREPROCESSING
I preprocessed the data by:

dropping non-beneficial columns,
finding the number of data points for each unique value for each of the columns that had more than 10 unique values - APPLICATION_TYPE and CLASSIFICATION,
choosing a cutoff point of 500 to bin rare categorical values together into a new value called "Other",
using pd.get_dummies() to convert categorical data to numeric,
dividing the data into a target array (IS_SUCCESSFUL) and features arrays,
applying the train_test_split to create a testing and a training dataset,
and finally, using StandardScaler to scale the training and testing sets

The model was required to achieve a target predictive accuracy higher than 75%. I made three official attempts using machine learning and neural networks. They all resulted in the same accuracy rate – right around 72%, so a little short of the required target accuracy.



Results from each model attempt are attached


Summary: 

In the three attempts I made, the model was unable to achieve a target predictive accuracy higher than 72.8%. Hypertuning resulted in virtually no improvement. I would consider using another classification model to see if it is better at predicting whether applicants will be successful if funded by Alphabet Soup..