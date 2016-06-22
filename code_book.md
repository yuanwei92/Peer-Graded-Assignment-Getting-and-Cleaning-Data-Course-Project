# Code book
This is the code book for tidy data set

## Variables Description
Data read from project data files. For description of each data files, refer to README in the project folder.

feature_list - features.txt file

activity - activity_labels.txt file

subject_test - subject_test.txt file

x_test - X_test.txt

y_test - Y_test.txt

subject_train - subject_train.txt

x_train - train/X_train.txt

y_train -train/Y_train.txt

### Processing variables
y_test_label - match y_test labels with corresponding activities

tidy_test - binding test subject, test activity and test set

y_train_label - match y_train labels with corresponding 
activities

tidy_train - binding train subject, train activity and train set

tidy_set - merged test set and train set

tidy_mean_std - data set with only measurements on the mean and standard deviation for each measurement

tidy_avg - independent tidy data set with the average of each variable for each activity and each subject. 