# Neutral_Charity_Analysis
# Overview 
  The point of this assingment is to assist with Bek to create a binary classifer to determine whether or not applicants will be successful by being funded by Alphabet Soup. Majority of the assignment is using machine learning and neural networks. 
  
# Results 
## Data Processing
1. The IS_SUCCESSFUL variable had been chosen to be a target for the model 
2. For this model, every variable except two will be used to as a feature
3. There were two variable that were neither target nor a feature and were dropped ("EIN" and "NAME")
## Compiling, Training, and Evaluating the Model
1. For a original neural network model, I had chosen to do two layers with 100 neurons for the first layer and 25 for the second layer. The activation for the first layer was "relu" and for the second layer is was "sigmoid".
2. I was not able to achieve the 75% target model performance
3. There were several methods that were done to increase the model performance. Such as changing the activation, including additional layer and changing the number of neurons. 

# Summary
The original model had a accuracy score of 72% for the neural network. However, I was not able to increace my model more than 72%, two out of the three additional model I ran outputted to 72%. There was one model that below 50%, which could have been caused by combination i had chosen for that particular model. I believe if there given a larger dataset than an accuray score of 75% would have been achieved or have different variables to be the target. 
