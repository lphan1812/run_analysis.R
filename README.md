# run_analysis.R

This repository contains the following files- 1) Raw Data 2) Script run_analysis.r 3) Tidy Data 4) Code Book

Raw Data
The data can be obtained from: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The full description of the data can be obtained from http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Script run_analysis.R - this script does the following:
Step 0: Download file, unzip file, and read in files.

Step 1: Merges the training and the test sets to create one data set.

Step 2,3,4: After merging the data, I use the the features and labels as the column names so it's easier to extract mean and std using grep.

Step 5: Then from the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

After executing, the dataset maybe found at ./tidydata.txt

Code Book: The code book contains the information about the variables and the data.
