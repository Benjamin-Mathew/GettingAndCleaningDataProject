# Getting and Cleaning Data - Week 4 Project

This is the course project for the Getting and Cleaning Data Coursera course. The R script, run_analysis.R, does the following:

-Downloads the dataset if it does not already exist<br/>
-Loads the activity and feature info<br/>
-Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation<br/>
-Loads the activity and subject data for each dataset, and merges those columns with the dataset<br/>
-Merges the two datasets<br/>
-Converts the activity and subject columns into factors<br/>
-Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.<br/>
-The end result is shown in the file tidy.txt.<br/>
