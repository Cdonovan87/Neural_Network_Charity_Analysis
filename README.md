# Neural_Network_Charity_Analysis
## Overview
For this Challenge I was Tasked with creating a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup using neural networks and machine learning.
## Results
* Data Preprocessing
  * The variables that are considered target for this model are would be the Is succesful variable as that is what
    we are trying to predict.
  * The variables considered features are all the other variables except for the ones that were dropped, name and       ein for the initial model and Special considerations for the optimization attempts.
* Compiling, Training, and Evaluating the model
  * Initial model:
      * I used two hidden layers with 80 and 40 neurons respectively. I used a sigmoid activation for my output             layer.
      * The model ended with an accuracy of 72.4% which was well low of the desired 75%
  * Attempt 1:
      * For this attempt I removed the special consideration column and increased the number of epochs from 100 to          150. I kept the same number of neurons for both hidden layers as before.
      * This attempt increased the accuracy to 72.7% which is slightly better but still short of 75%
  * Attempt 2:
      * In this attempt I took attempt one and doubled the number of neurons for both hidden layers.
      * Doing this brought back an accuracy of 72.4% which was back to the original model and well low of 75%
  * Attempt 3:
      * For this attempt i reverted back to 80 and 40 neurons for layers 1 & 2 and added a third layer of 20                neurons.
      * This brought back an accuracy of 72.5% which is an increase from attempt 2 but still lower than 75%.
  * Attempt 4: 
      * For the final attempt I reverted back to attempt one, as this attempt increased the initial model accuracy          the most, and I lowered the epochs back to 100 to see if that would increase the accuracy.
      * Accuracy came back as 72.5% short of 75%.
## Summary
Overall I was not able to increase the model to the desired 75% accuracy but was able to increase the initial model although it was only by a small amount. In order to be more accurate we could increase the number of data points for the model to train on. Since we were only looking to see if something was succesful or not we could have used logistic regression model since the outcome is binary.
