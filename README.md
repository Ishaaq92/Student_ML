# Student_ML
This is a Linear Regression Model that tried to predict students' final grades. 

All features are decalared and clarified in the student.txt file. 
In trying to fix the overfitting I removed almost all features to see how the model would behave. 
The cross validation cost was still over 200 times larger than the training cost.
Meaning that too many features is not the cause of overfitting. 
The data has also been normalised so that also is not the issue.
The model also does not contain complex features like polynomial terms.

Possible causes
  1. I ran too many epochs of iterations.
  2. Not enough regularisation.
