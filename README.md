# Getting and Cleaning Data - Course Project

This is the course project for the Getting and Cleaning Data Coursera course.
The R script, [run_analysis.R](run_analysis.R), does the following:
1. Download the dataset if it does not already exist in the working directory and unzip it.
2. Load the activity and feature information.
3. Loads both the training and test datasets, keeping only those columns which reflect a `mean()`: Mean value or `std()`: Standard deviation.
4. Loads the activity and subject data for each dataset, and merges those columns with the dataset.
5. Merges the two datasets.
6. Converts the `activity` and `subject` columns into factors.
7. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The end result is shown in the file `tidy_data.txt`.

 [CodeBook.md](CodeBook.md) has the details about the features