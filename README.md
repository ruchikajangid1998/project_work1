# project_work1

The main task was anomalies detection in the datasets. First I had imported the necessary libraries for the project and then I read datasets one by one using Pandas library. I converted the dataset into a numerical dataset using the 'getnum' function which I have described in the code. 


Then I used One-class svm for anomaly detection and then made a new column for each dataset as 'pred'. The value of new column was '1' for normal datapoint and '-1' for abnormal datapoint. The same process was repeated for each dataset and we got to know about anomalies.
