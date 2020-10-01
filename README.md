# Getting and Cleaning Data Course Project 

* This is the project for the "Getting and Cleaning Data" course on Coursera in the data science specialisation by Johns Hopkins University
* The R-script `data_analysis.R` does the following:

  1. Checking if the data has already been downloaded, if not a directory to store the data is created and       the data is downloaded 
  2. The train and test data sets are combined for the observations X, the activity y and the subject,           respectivly
  3. The observations (features) are named according the file `features.txt` accompanying the data
  4. Extracting the observations on the mean and standard deviation for each measurement
  5. Replaces numeric labels for each activity with descriptiv activity names 
  6. Appropiatly labels the measurments, by removing `-` and `()` and capitalizing `Mean` and `Std`
  7. Creates a tidy data set with the average of each measurment for each activity and each subject; the         result is saved in `tidy_data.txt`



