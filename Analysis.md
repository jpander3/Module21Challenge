The Purpose of this analysis is to explain how the deep learning model was improved in order to achieve a better target performance. 

Results:

Data Preprocessing

1. What variable(s) are the target(s) for your model?
    * The target variable is the 'IS_SUCCESSFUL' column from application_df.
2. What variable(s) are the features for your model?
    * The feature variables are every other column from application_df. We know this because we drop the 'IS_SUCCESSFUL' in order to split the data.
3. What variable(s) should be removed from the input data because they are neither targets nor features?
    * Both 'EIN' and 'NAME' columns were removed from the input data.

Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
    * For the model, I used 10 hidden nodes in layer 1 and 5 hidden nodes in layer 2. These were guesses to have a starting place and those are favorable numbers especially reducing by half as we go to the next layer or subtracting 5.
2. Were you able to achieve the target model performance?
    * I was not able to achiece the target model performance.
3. What steps did you take in your attempts to increase model performance?
    * Instead of dropping both the 'EIN' and 'NAME' columns, I chose to only drop the 'EIN' column.

Overall, the deep learning model was around 73% accurate in predicting the classification problem. Using a model with greater correlation between input and output would likely result in higher prediction accuracy. This could be achieved by doing additional data cleanup up front, as well as by using a model with different activation functions and iterating until higher accuracy is reached.