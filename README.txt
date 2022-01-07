Author: Angie D. Ortega Romo
Date: December 5th 2021

I applied the random forest (RF) algorithm to automatically classify 
different hand gestures: rock, paper, scissors, and okay, into their correct
category. To find the best RF classifier for the Hand_Gestures_Data data 
set (11678 observations and 64 features), I proceded as follows:
  1. A preliminary treatment of the dataset  
  2. Implementation of the principal component analysis (PCA) 
  3. Three different trials of RF with different numbers of trees (100,200, and 300), 
     among which the best RF classifier for our data set was selected.


Hand_Gestures_Data: Dataset used for the classification task obtained from the Kaggle
data repository (https://www.kaggle.com/kyr7plus/emg-4). This folder contains four
different files, one for each class of data. 

Hand_Gestures_ML_RF.Rmd: The R Studio notebook containing code.

