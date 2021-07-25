# Neural_Network_Charity_Analysis
## Overview of the analysis:
The purpose of this analysis was to…

## Results:


### Data Preprocessing:

**What variable(s) are considered the target(s) for your model?**

- For the challenge, I used the “IS_SUCCESSFUL” column as my target variable.


**What variable(s) are considered to be the features for your model?**

- Since I used “IS_SUCCESSFUL” as my target variable, that means the variables that are considered to be features for this model is “STATUS”, “ASK_AMT”, “APPLICATION_TYPE”, “INCOME_AMT”, “SPECIAL_CONSIDERATIONS”, “AFFILIATION”, “CLASSIFICATION”, “USE_CASE”, and the “ORGANIZATION”  columns.

**What variable(s) are neither targets nor features, and should be removed from the input data?**

- In my AlphabetSoupCharity.ipynb file, the variables I removed was EIN and NAME, since having those two columns wouldn’t be helpful when predicting the accuracy for this model.

### Compiling, Training, and Evaluating the Model:


**How many neurons, layers, and activation functions did you select for your neural network model, and why?**

- For the AlphabetSoupCharity.ipynb file, there were…
	- 80 and 30 Neurons for the two hidden layers
	- 1 output layer
	- 2 Activation Functions: relu and sigmoid

I chose this for my neural network model because...

- For the AlphabetSoupCharity_Optimization.ipynb file, there were…
	- 80, 30, 40 Neurons for the three hidden layers
	- 1 output layer
	- 3 different Activation Functions attempted, but selected relu and sigmoid

I chose this for my optimication neural network model because...

**Were you able to achieve the target model performance?**

- No, I wasn’t able  to achieve the target model performance even after my three attempts.

**What steps did you take to try and increase model performance?**

- I changed the number of epochs, changed the activation function, added a third hidden layer to my model, tried adding the ‘ORGANIZATION’ column to be dropped, and also tried changing the number of neurons for my “hidden_nodes” layers.


## Summary: 
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
