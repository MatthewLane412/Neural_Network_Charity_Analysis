# Neural_Network_Charity_Analysis

## Overview

This anlaysis was completed with neural network libraries such as Tensorflow in Python Jupyter Notebooks. This is another type of machine learning to predict outcomes. In this case, we were predicting if a loan would be successful. Some of the methods we used were training and splitting the data, using pandas dataframes and using the StandardScaler, OneHotEncoder. 


## Results

#### AlphabetSoupCharity
In this analysis we initially had the accuracy score up to 53%. This is based on the guidelines given by the class rubric. 

![PyBer_Summary_df](/Images/Epoch.PNG)

#### AlphabetSoupCharity_Optimization
In tis analysis, the accuracy score was the same at 53% by adding to the hidden layers

![PyBer_Summary_df](/Images/Epoch_Optimization.PNG)

#### AlphabetSoupCharity_Optimization_v1
In this analysis, the accuracy score was a little lower at just under 53%, This method used the activation fuction tanh.

![PyBer_Summary_df](/Images/Epoch_Optimization_v1.PNG)

#### AlphabetSoupCharity_Optimization_v2
In this analysis the machine learning jumped to 73%. This method used an increased number of units in the hidden layer and dropped additional columns before the analysis such as "Income_AMT" and "ASK_AMT". Dropping the "Income_AMT" column with over 8,000 unique values helped the model emensily.

![PyBer_Summary_df](/Images/Epoch_Optimization_v2.PNG)



## Summary
In conclusion python is a great language for machine learning. The tensorflow library makes machine coding much easier with many of the functions prebuilt, only needing information plugged in. With machine learning, the best outcome isn't going to happen on the first try. Practicing with the information and plugging in different values helps get the best machine learning outcome. Sometimes different layers need to be added or deleted, sometimes columns need to be dropped, other times additional epochs should be added. It all depends what data we are working with and getting the most out of our data without overfitting.

