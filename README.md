# deep-learning-challenge

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Using machine learning and neural networks, the purpose of this analysis is to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

The CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. 

## Results:

# The model uses the feature: 
'IS_SUCCESSFUL'

# Feature variable(s) for the model: 
The feature variables include APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.

# Variable(s) removed from the input data: 
EIN and NAME columns were removed from the input data as they are IDs columns and not useful as targets.

# Feature variable NAME has been brought back in the last model.
The model consists of three layers of neurons with 120, 60 and 1 neurons, relu functions with sigmoid output.

![image](https://github.com/anamatoc/deep-learning-challenge/assets/132319304/2c2c6c11-b2cf-4c48-af4f-74de70f2d8fe)

This model did not reach the desired goal of 75%:
268/268 - 0s - loss: 0.5712 - accuracy: 0.7290 - 479ms/epoch - 2ms/step.
Loss: 0.5711689591407776, Accuracy: 0.7289795875549316

Running again 4 more models and the one with the highest efficiency (Starter_Code-Copy2):

The feature variables include APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT. The target variable, IS_SUCCESSFUL', has three layers of neurons (120).
with three neuron layers (120, 60, 1)

## Achievement of the target model performance (Starter_Code-Copy5.0)
The model achieved a performance of 78% with several attempts to optimize the model as input data and training regime.

![image](https://github.com/anamatoc/deep-learning-challenge/assets/132319304/dbb3d25d-95ff-4de7-bdf2-eff89f7d0e40)


## Steps taken in attempts to increase model performance
Removed columns that did not add value.
Create more garbage cans and adjust the values of each garbage can
Add more neurons
Removing or adding layers.

## Summary:
The first 3 attempts did not lead to significant change, but on the fifth attempt, the model achieved an accuracy performance of 78.89% on the Alphabet success prediction. Further exploration of the data and models could lead to better prediction performance.

