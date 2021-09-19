# Neural_Network_Charity_Analysis
## Overview of the analysis
I will use the features in the provided dataset of the machine learning and neural network knowledge to help Beks create a binary classifier that is capable of predicting whether an organization will receive funding from Alphabet Soup. To be specific, Scikit learn and TensorFlow will be used to create a binary classification. Generally, we will.

## Results
Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing
Firstly, Bucketing or binning some the values to decrease the feature amount. Then, I need to preprocess the data by categorical data into numerical data by using the OneHotEncoder() module from sklearn. Finally, I merged the application_dataframe with the encode_dataframe and apply StandardScaler() function to normalized the data.
For this model, IS_SUCCESSFUL column is the target, EIN and NAME are neigher targets nor features, so those should be removed, and the rest of the columns are considered the feature. 


### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take to try and increase model performance?

## Summary
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
