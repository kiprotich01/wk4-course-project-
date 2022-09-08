# wk4-course-project-

The dataset includes the following files:
1. README.md : explains how all of the scripts work and how they are connected
2. CodeBook.md : describes the variables, the data, and any transformations or work that you performed to clean up the data
3. run_analysis.R : 
    Merges the training and the test sets to create one data set.
    
    Extracts only the measurements on the mean and standard deviation for each measurement. 
    
    Uses descriptive activity names to name the activities in the data set
    
    Appropriately labels the data set with descriptive variable names. 
    
    creates a second, independent tidy data set with the average of each variable for each activity and each subject.
4. ReadMe.txt

5. features_info.txt: Shows information about the variables used on the feature vector.

6. features.txt : List of all features.

7. activity_labels.txt : Links the class labels with their activity name.

8. train/X_train.txt : Training set.

9. train/y_train.txt : Training labels.

10. test/X_test.txt : Test set.

11. test/y_test.txt: Test labels.


The following files are available for the train and test data. Their descriptions are equivalent. 

* 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 

* 'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal from the smartphone accelerometer X axis in standard gravity units 'g'. Every row shows a 128 element vector. The same description applies for the 'total_acc_x_train.txt' and 'total_acc_z_train.txt' files for the Y and Z axis. 

* 'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration. 

* 'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second. 

NOTE 
- The features are normalized and bounded within [-1,1].
-Each feature vector is a row on the text file.
