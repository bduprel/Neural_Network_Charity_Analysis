# Neural_Network_Charity_Analysis

##Overview

This project was done to try and evaluate the likelihood a customer of Alphabet Soup would repay a loan if they were approved. This was done filtering and cleaning data down to then train and evaluate a model to predict likelihood to repay a loan. 

##Results

•	Data Preprocessing
o	What variable(s) are considered the target(s) for your model?
o	What variable(s) are considered to be the features for your model? 
	The variables that were focused on in this model were 'STATUS', 'ASK_AMT', 'IS_SUCCESSFUL', 'APPLICATION_TYPE', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT'. 
	With the dependent variable being “IS_SUCSESSFUL”. This was used to rate accuracy, and with this model came to just over 53%, which is not strong. 
o	What variable(s) are neither targets nor features, and should be removed from the input data?
	"USE_CASE_Other","AFFILIATION_Other" were dropped from the model.
•	Compiling, Training, and Evaluating the Model
o	How many neurons, layers, and activation functions did you select for your neural network model, and why?
	Two hidden layers were used. This is because the data was not thought to be too complex. 
o	Were you able to achieve the target model performance?
	I was not. The best I could accomplish was 53% accuracy 
o	What steps did you take to try and increase model performance?
	I tried adding more layers and different layer methods by switching to relu. 


### Optimization
Attempt 1
![image](https://user-images.githubusercontent.com/106126621/196847643-ce45eda7-72fa-443a-ace9-6ee503ec1b6a.png)

![image](https://user-images.githubusercontent.com/106126621/196847695-6e594169-c65c-48d6-8d95-09c3776e57a3.png)

Attempt 2
![image](https://user-images.githubusercontent.com/106126621/196847227-4290d046-49b8-4845-9978-3c51d9f81452.png)

![image](https://user-images.githubusercontent.com/106126621/196847282-b77ade60-5d8d-43e3-943f-139e48fd4300.png)

Attempt 3
![image](https://user-images.githubusercontent.com/106126621/196847471-4b042f94-1a7a-411b-836c-f0a3fb459002.png)

![image](https://user-images.githubusercontent.com/106126621/196847373-c6d0e69f-bb29-4e22-aebe-47188542b837.png)


## Summary
It seems this model may be victim to overfitting. I tried both 4 and 5 layers with both showing a decreased level of accuracy. It may have also been that the wrong methods were attempted when trying to layer the model 
