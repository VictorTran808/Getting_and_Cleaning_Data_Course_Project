# Getting_and_Cleaning_Data_Course_Project
The purpose of this project is to demonstrate my ability to collect, work with, and clean a data set.
The goal is to prepare tidy data that can be used for later analysis.
This is my submission of the week 4 course project assignment

### Data description
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The data is retrieved from:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones


### New tidydata
The new tidy data contained variables calculated based on the mean and standard deviation. Each row of the dataset is an average of each activity type for all subjects. With each column name label from the descriptive variables names.

### Explaination of R Script
There is only one R script call run_analysis.R which does the following:

1. Read all components of the training and test datasets as well as the features and activity labels data into rstudio

2. Merges the training and the test sets to create one data set.
Use command rbind to combine training and test set

3. Extracts only the measurements on the mean and standard deviation for each measurement.

4. Uses descriptive activity names to name the activities in the data set

5. Appropriately labels the data set with descriptive variable names.

6. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

