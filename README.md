---
title: "README"
author: "Adream"
date: "1/12/2020"
output: html_document
---

# Peer-graded Assignment: Getting and Cleaning Data Course Project

This repository is a submission for the Getting and Cleaning Data course project. Included are instructions on how to run the analysis file using the dataset.

## Dataset
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip


## Files
**CodeBook.md** is a code book that describes the variables, the data, and work that was performed to clean up the data

**run_analysis.R** is a script that performs the data preparation and follows the 5 steps below:

1. Merges the training and the test sets to create one data set.

2. Extracts only the measurements on the mean and standard deviation for each measurement.

3. Uses descriptive activity names to name the activities in the data set

4. Appropriately labels the data set with descriptive variable names.

5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable           for each activity and each subject.
        
**FinalTidyData.txt** is the exported final data after going through all the sequences described above.
