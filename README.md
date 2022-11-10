# Neural Network Charity Analysis

## Overview of the analysis: 
Use machine learning and neural networks to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

#
## Deliverables:
Deliverable 1: Preprocessing Data for a Neural Network Model
Deliverable 2: Compile, Train, and Evaluate the Model
Deliverable 3: Optimize the Model
Deliverable 4: A Written Report on the Neural Network Model

#
## Tools:
- Github
- Gitbash
- Jupyter Notebook
- Anaconda
- Python
- Scikit-Learn

#
## Results:

### Data Preprocessing:
- What variable(s) are considered the target(s) for your model? IS_SUCCESSFUL

- What variable(s) are considered to be the features for your model? APPLICATION_TYPE and CLASSIFICATION 


- What variable(s) are neither targets nor features, and should be removed from the input data? EIN, NAME, and USE_CASE.

### Compiling, Training, and Evaluating the Model:
- How many neurons, layers, and activation functions did you select for your neural network model, and why? For the initial model, there were 2 hidden layers: hidden_layer1 with 50 neurons
and hidden_layer2 with 25.

- Were you able to achieve the target model performance? The best performance was with the first module with 73.10% accuracy, which is 1.9% below the threshold.

- What steps did you take to try and increase model performance?  In the consequent attempts, noisy variables were removed, and additional layers and increased neurons and epochs were implemented. Despite all efforts, accuracy stayed around 72.55%.


#
## Summary: 
Overall the model did relatively well. One of the factors that might be affecting the accuracy might be the overfitting of the model. For this particular dataset, the Random Forest classifier would be perhaps a better fit.