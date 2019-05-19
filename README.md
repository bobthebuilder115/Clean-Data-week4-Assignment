# Clean-Data-week4-Assignment


This repository is the submission for week 4 assignment of Getting and Cleaning Data course.

Data description:

The data X variables are sensor signals measured using waist-mounted smartphone from 30 subjects. The data Y variable provides infomation on activity type the subjects performed during recording.

Code explaination:

The code combines the training and test datasets and extracted partial variables to create another dataset with the averages of each variable for each activity.

New dataset:

The new generated dataset contained variables calculated based on the mean and standard deviation. Each row of the dataset is an average of each activity type for all subjects.

The instruction for this assignment:

The R script called run_analysis.R does the following. 
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set.
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
