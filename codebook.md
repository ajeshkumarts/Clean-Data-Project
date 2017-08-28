## Introduction
The script run_analysis.R performs the following steps described in the course project's definition.
1. Download the .zip file
2. Fix the Column Names
3. Merges the training and the test sets to create one data set
4. Extracts only the measurements on the mean and standard deviation for each measurement
5. Uses descriptive activity names to name the activities in the data set
6. Appropriately labels the data set with descriptive variable names
7. Create a tidy data set with write.table()
## Variables
XTrain, YTrain, XTest, YTest, SubjectTrain and SubjectTest contain the data from the downloaded files.
Master variable is used to merge the previous datasets to further analysis.
