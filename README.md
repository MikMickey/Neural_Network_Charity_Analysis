# Neural_Network_Charity_Analysis

## Analysis Overview
The analysis used the deep-learning neural networks with the TensorFlow platform, to predict where to make investments using the charity dataset that organizationss that have received funding. 

The following methods were used:
-   preprocessing the data for the neural network model,
-   compile, train and evaluate the model,
-   optimize the model.

## Resources
Data Source: charity_data.csv
Software: Python 3.7.7, Anaconda Navigator 1.9.12, Conda 4.8.4, Jupyter Notebook 6.0.3

## Results

### Data Preprocessing

variable(s) that are considered the target(s) for your model?

-   IS_SUCCESSFUL column is the target for this model. It contains data refering to weither or not the charity donation was used effectively.

variable(s) that are considered to be the features for your model

-   Categorical variables: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS

variable(s) are neither targets nor features were removed

-   Columns EIN and NAME are identification information and have been removed from the data


First features we drop are the 'EIN' & 'NAME' because we expect both features to have little to do with our outcome.

-   The columns EIN and NAME are identification information and have been removed from tThe column IS_SUCCESSFUL contains binary data refering to weither or not the charity donation was used effectively. This variable is then considered as the target for our deep learning neural network.he input data.


### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model

-  The neural network model is made of two hidden layers with 80 and 30 neurons. This is to test out a standard model and identify areas for improvement. 

Where you able to achieve the target model performance

-   The initial model did not receive the target model performance of 75%. Closed to target, 71% accuracy

What steps taken to try to increase model performance

-   Increased hidden layers and number of neurons. Changed activation types and increased the number of Epoch.
    Methods used yielded an accuracy score of 71%

## Summary

The model accuracy ended up being 71% - with the dataset, predicted whether or not the project would be successful on all of the features that we used after dropping two features that that are irrelevant. 

The deep learning model was not optimized for optimal target performance to identify which charities to invest in. Maybe more data can increased the accuracy or use of different model - supervised machine learning to evaluate the performance against deep learning model.

