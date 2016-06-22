# Introduction
This is my submission for Peer Graded Assignment: Getting and Cleaning Data Course Project.

## Data Source
Data for this project was obtain from the Coursera assignment instructions. Data represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

[http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones]

Data for the project:

[https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip]

## Analysis File Description
The run_analysis.R can be run as long as setting your working directory to the UCI HAR Dataset folder. Dplyr package was required to run this script.

Analysis will read all the test data and train data merge them into one data set. Each variables were names accordingly based on the features listed in the features.txt file.

Using the combined data set, independent tidy data set with the average of each variable for each activity and each subject was created and written into tidydataset.txt file.