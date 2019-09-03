# Getting_and_Cleaning_Data_Course_Project

# Assigment

The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.

# Data

A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data of the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

# Code structure

a) Load the data.table library

b) Dowload and unzip data

c) Merges the training data to create one data set.

d) Merges the test data to create one data set.

1. Merges the training and the test data to create one data set.

2. Extracts only the measurements on the mean and standard deviation for each measurement.

3. Uses descriptive activity names to name the activities in the data set

e) Appropriately labels the data set with descriptive variable names.

5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

# Code Book
The CodeBook is contained in the file "CodeBook.md". It explains the transformations performed and the resulting data and variables in detail.

# Code script

The Code script for this project can be found in the file "Codescript.txt". It explains the transformations performed and the resulting data and variables in detail.

# How to run the project?

1. Set your working directory in R to where these project files are using the setwd() function
2. Run the code contained in the file "run_analysis.R" to make the analysis, this is the Code script for this project and it explains the transformations performed and the resulting data and variables in detail.
3. Step 3 will generate a file called tiny_data.txt 
