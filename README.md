# Deep Learning Homework: Charity Funding Predictor



### Overview

The purpose of this exercise is to create an algorithm via a neural network model used for predicting if applicants will be successful or not if funded by Alphabet Soup.   

A historical csv file (charity_data.csv), containing more that 34k organizations receiving funding from Alphabet Soup, was used for compiling the neural network model.  

### Results

- #### Data Processing

  - The primary target in this model is to predict if the applicants will be successful if funded by Alphabet Soup.   As such, the target column is "IS_SUCCESSFUL"  and contains the "yes "or "no" metadata we wish to predict.   
  - The features in this model are essentially all other columns with the exception of "IS_SUCCESSFUL", "EIN" and "NAME"
  - The "EIN" and "NAME" columns in the charity_data.csv file were considered as irrelevant and are neither targets for features.  Consequently,  both were removed from the neural network model configuration.     

  

- #### Compiling, Training, and Evaluating the Model

<img src="images/AlphabetSoupCharity_Accuracy_Score.PNG" height="50">

<img src="images/AlphabetSoupCharity_Accuracy_Chart.PNG" height="250">

