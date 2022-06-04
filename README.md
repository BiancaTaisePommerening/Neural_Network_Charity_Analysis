# **Neural_Network_Charity_Analysis**
Neural Networks and Deep Learning Models

## **Analysis Overview**


## **Results**



### **Data Preprocessing**

#### What variable(s) are considered the target(s) for your model?

The column "IS_SUCCESSFUL" is the target for the model which is represented by "y", where the goal is to predict if a charity is going to succed after the donation.

#### What variable(s) are considered to be the features for your model?

The following columns are the features of the model and they are represented by X:

- NAME	
- APPLICATION_TYPE
- AFFILIATION	CLASSIFICATION
- USE_CASE
- ORGANIZATION
- STATUS
- INCOME_AMT
- SPECIAL_CONSIDERATIONS	
- ASK_AMT


#### What variable(s) are neither targets nor features, and should be removed from the input data?

The column "EIN" was removed from the input data because it contain only unique identification values.

### **Compiling, Training, and Evaluating the Model**

#### How many neurons, layers, and activation functions did you select for your neural network model, and why?

- 3 hidden layers

- 100, 30, 10 neurons

- activation functions: relu for the first hidden layer, and sigmoid for the two other hidden layers and also for the output layer.




#### Were you able to achieve the target model performance?

- Yes, the performance achieved was 80%, which is a considerable improvement from the previous 73%.

#### What steps did you take to try and increase model performance?

- Inumerous testes where performed trying different combinations of hidden layers, neurons, and activation functions.
But one of the steps that actually made the difference was to keep the column NAMES, which at first may seem like it contain only unique values since they are identifications. But when investigating it, it actually does not have only unique values which then should be included on the prediction analysis.

The names are not unique values, so in likelihood the funding weighs in where the request comes from. Therefore it is a feature the neural net should include too

## **Summary**

 Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.









----------------------------------------------------------------------------------------------




Deliverable 4 Instructions
For this part of the Challenge, you’ll write a report on the performance of the deep learning model you created for AlphabetSoup.

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions.
