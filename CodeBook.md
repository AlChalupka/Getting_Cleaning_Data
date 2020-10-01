# Code Book 


### Data Describtion

The data collected from the accelerometers from the Samsung Galaxy S smartphone and can be downloaded from http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones. 

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

### Data Transformation 

The R-file `data-analysis.R` performs the following data transformations: 

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


### Variable describtion 
The following variables and their mean values for each subject and activity can be found in `tidy_data.txt`. 

| Variable Name         | Description                                                        |
| --------------------- | :------------------------------------------------------------------ |
| activity              | The activity performed
| subject               | Subject ID
| tBodyAccMeanXYZ       | Mean time for acceleration of body in direction X,Y,Z
| tBodyAccStdXYZ        | Standard deviation for time for acceleration of body in direction X,Y,Z
| tGravityAccMeanXYZ    | Mean time of acceleration of gravity in direction X,Y,Z
| tGravityAccStdXYZ     | Standard deviation for time of acceleration of gravity in direction X,Y,Z
| tBodyAccJerkMeanXYZ   | Mean time of body acceleration jerk in direction X,Y,Z
| tBodyAccJerkStdXYZ    | Standard deviation for time of body acceleration jerk in direction X,Y,Z
| tBodyGyroMeanXYZ      | Mean body gyroscope measurement in direction X,Y,Z
| tBodyGyroStdXYZ       | Standard deviation of body gyroscope measurement in direction X,Y,Z
| tBodyGyroJerkMeanXYZ  | Mean jerk signal of body in direction X,Y,Z
| tBodyGyroJerkStdXYZ   | Standard deviation of jerk signal of body in direction X,Y,Z
| tBodyAccMagMean       | Man magnitude of body Acc
| tBodyAccMagStd        | Standard deviation of magnitude of body Acc
| tGravityAccMagMean    | Mean gravity acceleration magnitude
| tGravityAccMagStd     | Standard deviation of gravity acceleration magnitude
| tBodyAccJerkMagMean   | Mean magnitude of body acceleration jerk
| tBodyAccJerkMagStd    | Standard deviation of magnitude of body acceleration jerk
| tBodyGyroMagMean      | Mean magnitude of body gyroscope measurement
| tBodyGyroMagStd       | Standard deviation of magnitude of body gyroscope measurement
| tBodyGyroJerkMagMean  | Mean magnitude of body body gyroscope jerk measurement
| tBodyGyroJerkMagStd   | Standard deviation of magnitude of body body gyroscope jerk measurement
| fBodyAccMeanXYZ       | Mean frequency of body acceleration in direction X,Y,Z
| fBodyAccStdXYZ        | Standard deviation of frequency of body acceleration in direction X,Y,Z
| fBodyAccJerkMeanXYZ   | Mean frequency of body accerlation jerk in direction X,Y,Z
| fBodyAccJerkStdXYZ    | Standard deviation of frequency of body accerlation jerk in direction X,Y,Z
| fBodyGyroMeanXYZ      | Mean frequency of body gyroscope measurement for X direction
| fBodyGyroStdXYZ       | Standard deviation of frequency of body gyroscope measurement for X direction
| fBodyAccMagMean       | Mean frequency of body acceleration magnitude
| fBodyAccMagStd        | Standard deviation of frequency of body acceleration magnitude
| fBodyBodyAccJerkMagMean| Mean frequency of body acceleration jerk magnitude
| fBodyBodyAccJerkMagStd| Standard deviation of frequency of body acceleration jerk magnitude
| fBodyBodyGyroMagMean  | Mean frequency of magnitude of body gyroscope measurement
| fBodyBodyGyroMagStd   | Standard deviation of frequency of magnitude of body gyroscope measurement
| fBodyBodyGyroJerkMagMean| Mean frequency of magnitude of body gyroscope jerk measurement
| fBodyBodyGyroJerkMagStd| Standard deviation frequency of magnitude of body gyroscope jerk measurement
