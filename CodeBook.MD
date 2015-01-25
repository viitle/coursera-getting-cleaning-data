
## Getting and Cleaning Data - Course Project

### Code Book

##### January 2015 edition

This file contains a code book that describes the variables, the data, and any transformations or work that was performed to clean up the data.

The data were downloaded from [Coursera class website](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip).

The R script `run_analysis.R` perform the 5 step described in the course project's definition.

This is the description of implementation of 5 steps performed by R script:

    1. The data contained in *test* and *train* file are merged each other by row.
       The variables x_data, y_data and subject_data contain the merged data.

    2. The variables containing the values of the mean and standard deviation for each measurement are extracted from the x_data data set.
       The name of variables are stored in `features.txt` file provided by initial data set.

    3. The variable of data set were named appropriately with the name provided by file activity_labels.txt.
       The only one variable of y_data data set was named "activity".

    4. The only one variable of subject_data data set was named "subject".

    5. In this step was produced the tidy data set, named "out_average_tidy_data.txt",
       which contains the average of each variable for each activity and each subject.

