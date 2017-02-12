# Getting and Cleaning Data Project

This is the course project for the Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, does the following:

1. The script will download the dataset if it does not already exist in the working directory.
2. The scrpt will load the activity and feature info.
3. The training and test datasets will be loaded, keeping only those columns which
   reflect a mean or standard deviation.
4. The script will load the activity and subject data for each dataset, and merges those
   columns with the dataset.
5. The two datasets will be merged.
6. The `activity` and `subject` columns will be merged into factors.
7. Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.

The end result is shown in the file `tidy.txt`.
