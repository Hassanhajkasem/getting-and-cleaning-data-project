# Getting and Cleaning Data Project

## 💡 Overview

This project demonstrates the cleaning and tidying of data collected from the accelerometers of the Samsung Galaxy S smartphones. The goal is to transform raw data into a tidy dataset that contains the average of each variable for each activity and each subject.

## 📁 Project Files

- `run_analysis.R`: The R script that performs data merging, extraction, labeling, and tidying.
- `tidy_dataset.txt`: The final tidy dataset produced by `run_analysis.R`.
- `CodeBook.md`: A markdown document that describes the variables, data, and transformations.
- `README.md`: This explanation file.

## 📌 How to Reproduce This Project

1. Download the dataset from:  
   [UCI HAR Dataset](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

2. Unzip the archive into the root directory of your R project.

3. Run the R script:  
   ```r
   source("run_analysis.R")

