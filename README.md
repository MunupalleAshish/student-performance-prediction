# student-performance-prediction
Predict student grades using Linear Regression
# Student Performance Prediction using Linear Regression

# Algorithm Used
I used Linear Regression to predict students' final grades.  
This algorithm looks at how different factors like study time, past failures, absences, and previous grades affect the final grade.  
It is simple and easy to understand.

# Dataset Used
The dataset comes from the UCI Machine Learning Repository.  
- Features used:
  - studytime - weekly study time  
  - failures - number of past class failures  
  - absences - number of school absences  
  - G1 - first period grade  
  - G2 - second period grade  
- Target:
  - G3 - final grade  
- The dataset has 395 rows and 33 columns.

## Output Metrics
After training the model on most of the data and testing on the rest, the results are:  

- Mean Absolute Error (MAE): 1.34  
- R2 Score: 0.78  

This means the model predicts grades with an average error of about 1 to 2 points and explains most of the variation in grades.
