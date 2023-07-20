# deep-learning-challenge

## Neural Network Model Report

### Purpose
The purpose of this model is to predict if applicants will be successful if granted funding from the nonprofit foundation Alphabet Soup. Machine learning and neural networks will be used to predict the best chance of success of the applicants' ventures based on a dataset provided by Alphabet Soup. 

#### Data Processing
- What variable(s) are the target(s) for your model? The target variable is the 'IS_SUCCESSFUL' column from the dataset. 
- What variable(s) are the features for your model? The feature variables are all the other columns in the dataset with exception to the 'EIN' and 'NAME' columns. 
- What variable(s) should be removed from the input data because they are neither targets nor features? The 'EIN' and 'NAME' columns are removed from the dataset as they are neither targets nor features of the dataset. 

#### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why? The input features, and hidden node layers initial numbers were pre-selected and run for a baseline calculation. 
- Were you able to achieve the target model performance? An initial accuracy score of 73% did not meet the target performance.
- What steps did you take in your attempts to increase model performance? In an attempt to improve the accuracy of the model the number_input_features variable was changed to a pre-determined integer (30) and the hidden_nodes_layer1 and hidden_nodes_layer2 were adjusted multiple times. The accuracy score decreased with increases and decreases of the number_input_features and hidden_nodes_layer1 and hidden_nodes_layer2. These adjustments did not yield an improved model. 

### Summary
This model was not very effective for the purpose of this challenge. An accuracy score of 73% is not high enough for a confident reliance on the model for predictions about the best chance of success. It is unclear at this time what kind of models would outperform this model but further investigation and study is needed to improve the reliability of this model for prediction purposes. 


