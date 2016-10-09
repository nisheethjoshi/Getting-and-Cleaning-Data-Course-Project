Getting and Cleaning Data

Course Project

You should create one R script called run_analysis.R that does the following.

Merges the training and the test sets to create one data set. Extracts only the measurements on the mean and standard deviation for each measurement. Uses descriptive activity names to name the activities in the data set Appropriately labels the data set with descriptive activity names. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. Steps to work on this course project

Original Data Source

Data for analysis is downloaded from the below URL https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Files Included in Repository

This repo includes following files - run_analysis.R - CodeBook.md - avgSujectActivities.txt

Details of run_analysis.R script

This is the script used to perform analysis on raw data to create a tidy datafile called tidydata.txt

Functions of run_analysis.R Script

Downloads the dataset from the URL mentioned above and unzips it to create UCI HAR Dataset folder Imports test and train datsets and creates data frames from then and then Merges the training and the test sets to create one data frame. Extracts a subset of data with only the measurements on the mean mean() and standard deviation std() for each measurement. Updates the variable names in dataframe variable names for data fame to improve readibility Appropriately labels the data set with descriptive activity names in place of activity Ids Reshapes dataset to create a data frame with average of each measurement variable for each activity and each subject Writes new tidy data frame to a text file to create the required tidy data set file

Details of CodeBook.md

The code book file describes the variables, the data, and any transformations and work performed to clean up the data.

Details of tidy Dataset file tidydata.txt

This is the tidy data file created after after running run_analysis.R script on the original data downloaded from this URL
