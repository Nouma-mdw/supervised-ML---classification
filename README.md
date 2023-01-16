# supervised-ML---classification
supervised ML classification - a little competition in class

In this repo you will find my competition code for classification. There are two main parts
## 1 initial data cleaning and feature selection
## 2 choice of ML algorithms; hypertuning with GridSearchCV, get_params().keys() and documentation
## and as part of number to the export of the results


Special notes;
- Checking on crossvalidation you might niotice, that I didn't use the ".predict" method from GridSearchCV.
When learning I need to visualize the process. Whereas get_params().keys() helped me see what was going on, I choose 
".best_scores_" and write by hand over the ".predict" to get more practice with the mdoels input parameters. 

