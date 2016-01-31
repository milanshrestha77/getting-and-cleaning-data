# Getting and Cleaning Data Course Project
### Requirement:

You should create one R script called "run_analysis.R" that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

### Steps to Run "run_analysis.R"
1. This R Script assums that Source Data has been downloaded in the folder "UCI HAR Dataset". 
2. R Script also need to be inside the same parent directory of "UCI HAR Dataset".
3. Script can be Run using command source("run_analysis.R")
4. This Should produce a dataset tidy_data.txt as a output.

**Note**: This Script depends on "data.table" and "dplyr" library

