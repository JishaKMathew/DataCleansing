The run_analysis.R script performs the data preparation and then followed by the 5 steps required as described in the course project’s definition.

Assign each data to variables

1. dataFeaturesNames <- features.txt : 561 rows, 2 columns

The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ.

2. activityLabels <- activity_labels.txt : 6 rows, 2 columns

List of activities performed when the corresponding measurements were taken and its codes (labels)

3. dataSubjectTest <- test/subject_test.txt : 2947 rows, 1 column

contains test data of 9/30 volunteer test subjects being observed

4. dataFeaturesTest <- test/X_test.txt : 2947 rows, 561 columns

contains recorded features test data

5. dataActivityTest <- test/y_test.txt : 2947 rows, 1 columns

contains test data of activities code labels

6. dataSubjectTrain <- train/subject_train.txt : 7352 rows, 1 column

contains train data of 21/30 volunteer subjects being observed

7. dataFeaturesTrain <- train/X_train.txt : 7352 rows, 561 columns

contains recorded features train data

8. dataActivityTrain <- train/y_train.txt : 7352 rows, 1 columns

contains train data of activities code labels

B. Merges the training and the test sets to create one data set
    dataCombine
C. Extracts only the measurements on the mean and standard deviation for each measurement
    tidydata.txt : 180 rows

D. Uses descriptive activity names to name the activities in the data set
  activityLabels

E. README
  Peer-graded Assignment: Getting and Cleaning Data Course Project

F.Dataset
  Human Activity Recognition Using Smartphones

G. Files
  CodeBook.md a code book that describes the details of the steps

H. Scripts
run_analysis.R performs the below steps

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
