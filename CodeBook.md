---
title: "Getting and Cleaning Data- CodeBook"
author: "Amanda Ramdass"
date: "10/19/2020"
output: html_document
---

### Description
Additional information about the variables, data and transformations used in Getting and Cleaning Data course in the course project for the Johns Hopkins.

### Source Data
Data + Description can be found here [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

### Data Set Information
For this project, the data inclduded a group of 30 volunteers within an age range of 19 to 48 years. The data was collected from each individual who perfromed performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) while wearing a smartphone (Samsung Galaxy S II) on their waist. Via an accelerometer and gyroscope in the phone, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. A video-recorded was done to label the data manually. Datasets obtained have been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

The accelerometer and gyroscope were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. A filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

### Attribute Information
For each record in the dataset it is provided: 
- Triaxial acceleration from the accelerometer, that is total acceleration, and estimated body acceleration. 
- Triaxial Angular velocity from the gyroscope. 
- A 561-feature vector with time and frequency domain variables. 
- Its activity label. 
- An identifier of the person who perforemed the experiment.

## Please see the README.md for how the following instructions are implemented to complete the project [README.md](https://github.com/mGalarnyk/datasciencecoursera/blob/master/3_Getting_and_Cleaning_Data/README.md)
### 1. Merge the training and the test sets to create one data set.
### 2. Extracts only the measurements on the mean and standard deviation for each measurement.
### 3. Uses descriptive activity names to name the activities in the data set
### 4. Appropriately labels the data set with descriptive variable names.
### 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.