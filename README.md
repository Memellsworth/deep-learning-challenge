# deep-learning-challenge

# PURPOSE
## The purpose of this activity is to help a charitable foundation Alphabet soup find a tool that can help them select the applicants for funding with the beswt chance of success in their ventures

# DATA PREPERATION 

## -From application_df, the target variable is "IS_SUCCESSFUL"
## -Found number of data points for each unique value for columns in APPLICATION_TYPE and CLASSIFICATION 
## - Dropped theu unnesssecary columns  "EIN" and "NAME" from the dataframe.

# COMPLILING, TRAINING & EVALUATING THE MODEL 

## In the first analysis, I used 80 nodes for the first layer and 30 for the second layer. This gave me an accuracy of 72.93%. In the second model, I kepy the same nodes for the first and second layer and added a third layer. I got 73.10% and after many attemps of increase and decreasing the nodes adding a fourth layer, i was not able to get this to 75%. I was also having a lot of difficulty getting the model to save as h5 file and I tried multiple different methods. 

# SUMMARY
# For this particular model, overall accuracy is 73.10% in prediction the success rate.