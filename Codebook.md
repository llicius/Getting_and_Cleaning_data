CodeBook
========

The data was obtained from:  
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip  

the steps followed by run_analysis.R are the following,  
 
- Read X_train.txt, y_train.txt and subject_train.txt        
- Read X_test.txt, y_test.txt and subject_test.txt
- Bind *testData* to *trainData*, bind *testLabel*, bind *testSubject* to *trainSubject*. 
- Read the features.txt file in a variable called *features*.
- Clean the column names of the subset.
- Read the activity_labels.txt file
- Transform the values of *joinLabel* according to the *activity* data frame.  
- Combine the *joinSubject*, *joinLabel* and *joinData* 
- Write the *cleanedData* out to "merged_data.txt"
- Write a final dataset with the average of each measurement 
- Generate "data_with_means.txt" file in the working directory. 
 
