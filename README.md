# Getting_And_Cleaning_Data

This file describes how the run_analysis.R script works.

    1. Unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".
   	 Make sure the folder "data" and the run_analysis.R script are both in the current working directory.

    2. In RStudio, use the command source("run_analysis.R").

    3. Look for two files produced in the current working directory:
        merged_data.txt containing the data frame called "cleanedData".
        tidy_data_with_means.txt containing the data frame called "output". 

    4. In RStudio, use the command data <- read.table("data_with_means.txt") to read the file. 
	 By taking the average of each of the 6 activities per 30 subjects, there will be 180 rows including the combinations for all 66 features.
	
