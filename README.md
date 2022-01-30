# Neural_Network_Charity_Analysis
Create a binary classifier that is able to predict whether applicants will be successful if funded by Alphabet Soup.
## Overview
We have been asked to help the foundation for Alphabet Soup  predict where to make investments. Using machine learning and neural networks, create a binary classifier that is capable of predicting whether applicants will be successful if they are funded by Alphabet Soup. 

## Results
### Data Preprocessing

* As a target for our model, we used the IS_SUCCESSFUL which indicates that the money was used successfully. We dropped the identification variables as they are neither features     or targets. 
* For our variables, we used the affiliation, use case, organization type, status and the income amount in our initial model. 
* To try to improve accuracy, we dropped the special considerations column. 


### Compiling, Training, and Evaluating the Model

* We started with 3 layers, hidden layer 1 with 8 neurons and relu activation, hidden layer 2 with 16 neurons and relu activation and the output layer using sigmoid activation.  

* Our accuracy was below 75%. 

   ![image](https://user-images.githubusercontent.com/89313168/151720449-8f40a8c9-ddff-4433-8a0c-96e71ba96d0f.png)


* We added an additional hidden layer and added neurons as well as changed the activation functions to attempt to improve the accuracy but we were unable to achieve results over     75%. 

   ![image](https://user-images.githubusercontent.com/89313168/151720516-a984bf30-8b38-47a0-aa77-51cc10fadebf.png)
   
 ## Summary
 I would not recommend using this model to predict where to invest. It might be beneficial to take another look at the data, consider if there is additional information that can  be removed to improve the accuracy of predictions. One could consider using different activation functions on the layers and/or adding more neurons to the hidden layers as well 



