# Neural_Networks_and_Deep_Learning_Models

## ***Project Overview***

  * Compare the differences between the traditional machine learning classification and regression models and the neural network models.
  * Describe the perceptron model and its components.
  * Implement neural network models using TensorFlow.
  * Explain how different neural network structures change algorithm performance.
  * Preprocess and construct datasets for neural network models.
  * Compare the differences between neural network models and deep neural networks.
  * Implement deep neural network models using TensorFlow.
  * Save trained TensorFlow models for later use.

## ***Resources***
  
  * Data Source: bank_telemarketing.csv, diabetes.csv, hr_datasets.csv, HR-Employee-Attrition.csv, loan_status.csv, ramen-ratings.csv, charity_data.csv
  * Software: Python 3.7.6, Anaconda 4.8.4, Jupyter Notebook 6.0.3
  
## ***Challenge Overview***

From Alphabet Soup’s business team, Beks, a data scientist received a CSV containing more than 34,000 organizations that have received various amounts of funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization.
Using my knowledge of machine learning and neural network model building, the team has asked me to create a binary classifier that is capable of predicting whether or not an applicant will be successful if funded by Alphabet Soup using the features collected in the provided dataset.

  * Import, analyze, clean, and preprocess a “real-world” classification dataset.
  * Select, design, and train a binary classification model of your choosing.
  * Optimize model training and input data to achieve desired model performance.
  
## ***Challenge Summary***

Be sure to identify the following in your dataset:

  * What variable(s) are considered the target for your model? - IS_SUCCESSFUL when i got an accuracy of 72% and SPECIAL_CONSIDERATIONS when i got an accuracy of 99.9%

  * What variable(s) are considered to be the features for your model? - APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, ORGANIZATION, INCOME_AMT, ASK_AMT, IS_SUCCESSFUL, and SPECIAL_CONSIDERATIONS

  * What variable(s) are neither and should be removed from the input data? - EIN, NAME, STATUS, USE_CASE
  
***Results:***

 * How many neurons and layers did you select for your neural network model? Why?
   * 1 input layer and 2 hidden_nodes_layer, then  were used. The number of nodes for each were 100. This number was achieved based on try and error to increase the accuracy of the model.
 * Were you able to achieve the target model performance? What steps did you take to try and increase model performance?
 * If you were to implement a different model to solve this classification problem, which would you choose? Why?
   
