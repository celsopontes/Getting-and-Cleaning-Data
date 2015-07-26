# Getting-and-Cleaning-Data
This repository contains the files of the Course Project of the Getting and Cleaning Data course.


## Course Project
All project-related materials can be found and downloaded at  https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive, say C:\Users\yourname\Documents\R\ (Or on your current Working Directory)

Put run_analysis.R into C:\Users\yourname\Documents\R\UCI HAR Dataset\ (Or on your current Working Directory)

In RStudio: setwd("C:\\Users\\yourname\\Documents\\R\\UCI HAR Dataset\\"), followed by: source("run_analysis.R")
(If you already put the files in your current working directory, you only need to do the second part: source("run_analysis.R"))

You can comment/uncomment the lines 59 and 58 of the code to get the file "data_set_with_the_averages.txt" without the row names. The new file will be named as "data_set_with_the_averages_rownames_FALSE.txt".

Use data <- read.table("data_set_with_the_averages.txt") to read the data. It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. Note that the provided R script has no assumptions on numbers of records, only on locations of files.
