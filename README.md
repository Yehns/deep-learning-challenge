# deep-learning-challenge
Module 21

 

**Purpose of the Analysis**
The aim of the analysis is to determine the best candidates to receive funding in their ventures based on application type, and financial characteristics. The major criteria will look at the amount of successful and unsuccessful applicants.

**What variable(s) are the target(s) for your model?**

The model uses a dataset which is occupied by 34,000 applicants which have applied for funding. The criteria include: 
**Target Variable:  **
-	IS_SUCCESSFUL
**Feature Variable: **
-	APPLICATION_TYPE	
-	AFFILIATION	
-	CLASSIFICATION	USE_CASE	
-	ORGANIZATION	STATUS	
-	INCOME_AMT	
-	SPECIAL_CONSIDERATIONS	
-	ASK_AMT	

**What variable(s) should be removed from the input data because they are neither targets nor features?**

The name and employee identification have been removed from the data. With this data included, a vast amount of columns are added which cannot be encoded in binary. 

**How many neurons, layers, and activation functions did you select for your neural network model, and why?**

The initial optimisation used two nodes (8 and 5 layers respectively), with relu functions for the hidden and sigmoid for the output layer and 100 epochs. Using this as the stating point offered an opportunity to change all features, and experiment with performance.

**Were you able to achieve the target model performance?**

I was not able to achieve the desired output of 0.75, the closes value was 0.726. 

**What steps did you take in your attempts to increase model performance?**


The first was to increase the amount of hidden layers from 2 to 3,changing the amount of layers in each (16, 8 and 4). Using sigmoid, tanh and relu; the most successful output layer worked with sigmoid, without using tanh. The relu graduation resulted in greater accuracy, in contrast to its s-shape counterparts. The epochs maintained at 100, as less dd not yield enough simulations, and more than 100 resulted in a bloated process. 


**Images to Compare Optimisation Attempt **

![image](https://github.com/Yehns/deep-learning-challenge/assets/118644844/34d52620-17db-44f8-ba43-23aa8d7bd0b3)

![image](https://github.com/Yehns/deep-learning-challenge/assets/118644844/fd590636-8f45-44eb-85ec-fd13f5c37ae4)
