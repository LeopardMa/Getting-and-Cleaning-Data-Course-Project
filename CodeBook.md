# Getting-and-Cleaning-Data-Course-Project

This is a a code book that describes the variables, the data, and transformations or work 
performed to clean up the data.

In order to clean up the data through R script, in run_analysis.R:
- It merges the training and the test sets to create one data set as "alldata".
- It extracts only the measurements on the mean and standard deviation for each measurement, 
   which is listed in List1 at the end of this file.
- It labels the data set with descriptive variable names according to the features listed in 'features.txt'.
- It creates a second, independent tidy data set with the average of each variable 
  for each activity and each subject as "tb2".


List1:<br>
"tBodyAcc-mean()-X"<br>
"tBodyAcc-mean()-Y"<br>
"tBodyAcc-mean()-Z"<br>
"tBodyAcc-std()-X"<br>
"tBodyAcc-std()-Y"<br>
"tBodyAcc-std()-Z"<br>
"tGravityAcc-mean()-X"<br>
"tGravityAcc-mean()-Y"<br>
"tGravityAcc-mean()-Z"<br>
"tGravityAcc-std()-X"<br>
"tGravityAcc-std()-Y"<br>
"tGravityAcc-std()-Z"<br>
"tBodyAccJerk-mean()-X"<br>
"tBodyAccJerk-mean()-Y"<br>
"tBodyAccJerk-mean()-Z"<br>
"tBodyAccJerk-std()-X"<br>
"tBodyAccJerk-std()-Y"<br>
"tBodyAccJerk-std()-Z"<br>
"tBodyGyro-mean()-X"<br>
"tBodyGyro-mean()-Y"<br>
"tBodyGyro-mean()-Z"<br>
"tBodyGyro-std()-X"<br>
"tBodyGyro-std()-Y"<br>
"tBodyGyro-std()-Z"<br>
"tBodyGyroJerk-mean()-X"<br>
"tBodyGyroJerk-mean()-Y"<br>
"tBodyGyroJerk-mean()-Z"<br>
"tBodyGyroJerk-std()-X"<br>
"tBodyGyroJerk-std()-Y"<br>
"tBodyGyroJerk-std()-Z"<br>
"tBodyAccMag-mean()"<br>
"tBodyAccMag-std()"<br>
"tGravityAccMag-mean()"<br>
"tGravityAccMag-std()"<br>
"tBodyAccJerkMag-mean()"<br>
"tBodyAccJerkMag-std()"<br>
"tBodyGyroMag-mean()"<br>
"tBodyGyroMag-std()"<br>
"tBodyGyroJerkMag-mean()"<br>
"tBodyGyroJerkMag-std()"<br>
"fBodyAcc-mean()-X"<br>
"fBodyAcc-mean()-Y"<br>
"fBodyAcc-mean()-Z"<br>
"fBodyAcc-std()-X"<br>
"fBodyAcc-std()-Y"<br>
"fBodyAcc-std()-Z"<br>
"fBodyAcc-meanFreq()-X"<br>
"fBodyAcc-meanFreq()-Y"<br>
"fBodyAcc-meanFreq()-Z"<br>
"fBodyAccJerk-mean()-X"<br>
"fBodyAccJerk-mean()-Y"<br>
"fBodyAccJerk-mean()-Z"<br>
"fBodyAccJerk-std()-X"<br>
"fBodyAccJerk-std()-Y"<br>
"fBodyAccJerk-std()-Z"<br>
"fBodyAccJerk-meanFreq()-X"<br>
"fBodyAccJerk-meanFreq()-Y"<br>
"fBodyAccJerk-meanFreq()-Z"<br>
"fBodyGyro-mean()-X"<br>
"fBodyGyro-mean()-Y"<br>
"fBodyGyro-mean()-Z"<br>
"fBodyGyro-std()-X"<br>
"fBodyGyro-std()-Y"<br>
"fBodyGyro-std()-Z"<br>
"fBodyGyro-meanFreq()-X"<br>
"fBodyGyro-meanFreq()-Y"<br>
"fBodyGyro-meanFreq()-Z"<br>
"fBodyAccMag-mean()"<br>
"fBodyAccMag-std()"<br>
"fBodyAccMag-meanFreq()"<br>
"fBodyBodyAccJerkMag-mean()"<br>
"fBodyBodyAccJerkMag-std()"<br>
"fBodyBodyAccJerkMag-meanFreq()"<br>
"fBodyBodyGyroMag-mean()"<br>
"fBodyBodyGyroMag-std()"<br>
"fBodyBodyGyroMag-meanFreq()"<br>
"fBodyBodyGyroJerkMag-mean()"<br>
"fBodyBodyGyroJerkMag-std()"<br>
"fBodyBodyGyroJerkMag-meanFreq()"<br>