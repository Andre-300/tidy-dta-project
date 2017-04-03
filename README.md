#Getting-and-Cleaning-Data-Week-4-Assignment 
**##INTRODUCTION**  

This repo was created to finish the assignment for week 4 of Getting and Cleaning Data Coursera course.

**##ABOUT THE RAW DATA**

The feutures (561) are unlabeled and can be found in the x_test.txt. The activity labels are in the y_test.txt file.Subjects are in the subject_test.txt file.

The same holds for the training data sets.

**##About the script and the tidy data set**

I created a script called run_analysis.R which will merge the test and training sets together. Prerequisites for this script:

1. the UCI HAR Dataset must be extracted and..
2. the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"

After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

Lastly, the script will create a tidy data set containing the means of all the columns per test subject and per activity. This tidy dataset will be written to a tab-delimited file called ```tidy.txt```, which can also be found in this repository.

##About the Code Book
The CodeBook.md file explains the transformations performed and the resulting data and variables.







