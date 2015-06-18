# Course Project
This project is about collecting, working with, and cleaning a data set.
The data set consists of measurements of the accelerometer and the gyroscope of the smartphone, Samsung Galaxy S II, that 30 people were wearing on their waist. The dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 
Here are the data for the project:  
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip .
The R script called run_analysis.R, that is in this repo, does the following:
* opens some txt files that contain the data, the variables, the activities and the subjects
* merges the training set, the training activities and the training subjects, _mergedtrain_ 
* merges the test set, the test activities and the test subjects, _mergedtest_
* labels the data sets with descriptive variable names
* merges the training and the test sets to create one data set
* excludes the variables(columns) that are dublicated
* extracts only the measurements on the mean and standard deviation for each measurement
* renames the variables in order to be readable, _mergeddata_
* uses descriptive activity names to name the activities in the data set, _data_
* Creates a tidy data set with the average of each variable for each activity and each subject, _dataset_
