GettingCleaningDataCourseProject
================================

This is the R script (run_analysis.R) for the Getting and Cleaning Data Course project. 

This script follows the steps outlined in the project guidelines:
	1. Merges the training and the test sets to create one data set.
	2. Extracts only the measurements on the mean and standard deviation for each measurement
		Means and standard deviations were only included into this set 
		if the mean or std was at the end of the variable name, 
		not with the first part of the variable name.
	3. Uses descriptive activity names to name the activities in the data set
	4. Appropriately labels the data set with descriptive variable names. 
	5. From the data set in step 4, 
	creates a second, independent tidy data set with the 
	average of each variable for each activity and each subject.
	
	
The output file (Means.txt) contains means for each subject for each of the activities 
for each of the means and standard deviation variables of the full dataset 
(66 variables, with Subject and Activity as IDs). 

 