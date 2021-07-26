# Neural_Network_Charity_Analysis
## Overview of the analysis:
The purpose of this analysis was to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if it was funded by Alphabet Soup. I had to use machine learning and make a neural network model that is compiled, trained, and evaluated for a dataset that contains 34,000 organizations. I also had to attempt getting the accuracy to be at least 75% or higher or just attempt it three times if I couldn’t.

## Results:

Accuracy results of my 3 different attempts:

<img width="517" alt="Neural network charity (3 attempts accuracy results)" src="https://user-images.githubusercontent.com/79742633/126947822-63edc9e7-3165-413e-89b4-310b57bf3d91.png">

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

I chose this for my neural network model because I felt having 2 different activation functions at once would help get more data.

- For the AlphabetSoupCharity_Optimization.ipynb file, there were…
	- 80, 30, 40 Neurons for the three hidden layers
	- 1 output layer
	- 3 different Activation Functions attempted, but selected relu and sigmoid for this model

I chose this for my optimization neural network model because I felt the shape of the relu and sigmoid activation function would cover the most data when ran.

**Were you able to achieve the target model performance?**

- No, I wasn’t able  to achieve the target model performance even after my three attempts.

**What steps did you take to try and increase model performance?**

- I changed the number of epochs, changed the activation function, added a third hidden layer to my model, tried adding the ‘ORGANIZATION’ column to be dropped, and also tried changing the number of neurons for my “hidden_nodes” layers.


## Summary: 
The overall results of the deep learning model are 72.47% for the AlphabetSoupCharity and 72.24% for the AlphabetSoupCharity_Optimization even after making those changes I mentioned above. I recommend using a different model like RandomForestClassifier because that model would allow me to find the important features better, which means it would be able to perform better on this large dataset.
