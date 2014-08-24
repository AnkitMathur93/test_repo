#Human Activity Recognition Using Smartphones Dataset
##Version 1.0
==================================================================
###Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto.
###DITEN - Università degli Studi di Genova.
###Via Opera Pia 11A, I-16145, Genoa, Italy.
####activityrecognition@smartlab.ws
####www.smartlab.ws
==================================================================

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years.
Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone 
(Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity 
at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly 
partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows 
of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, 
was separated using a Butter-worth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low 
frequency components, therefore a filter with 0.3 Hz cut-off frequency was used. From each window, a vector of features was obtained by 
calculating variables from the time and frequency domain.

==================================================================

The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals 
(prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass 
Butter-worth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and 
gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butter-worth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). 
Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag,
 tBodyGyroJerkMag). 

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, 
fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 

These signals were used to estimate variables of the 561 variable feature vector 


===================================================================

The Tidy data set that is returned by the run_analysis.R extracts a subset of the above mentioned measurements.
Variables which are mean and StandardDeviation of the measurements are included in the dataset.
Each record in the tidy dataset are average of each variable for each activity and each subject. 

===================================================================
###Following is the list of the column fields(variables) of the dataset.

####Subject_Id






####Activity_Id






####Activity_Label






####tBodyAccelerationMean_Xaxis






####tBodyAccelerationMean_Yaxis






####tBodyAccelerationMean_Zaxis






####tGravityAccelerationMean_Xaxis






####tGravityAccelerationMean_Yaxis






####tGravityAccelerationMean_Zaxis






####tBodyAccelerationJerkMean_Xaxis






####tBodyAccelerationJerkMean_Yaxis






####tBodyAccelerationJerkMean_Zaxis






####tBodyGyroMean_Xaxis






####tBodyGyroMean_Yaxis





####tBodyGyroMean_Zaxis





####tBodyGyroJerkMean_Xaxis





####tBodyGyroJerkMean_Yaxis





####tBodyGyroJerkMean_Zaxis





####tBodyAccelerationMagMean





####tGravityAccelerationMagMean





####tBodyAccelerationJerkMagMean





####tBodyGyroMagMean





####tBodyGyroJerkMagMean





####fBodyAccelerationMean_Xaxis






####fBodyAccelerationMean_Yaxis






####fBodyAccelerationMean_Zaxis






####fBodyAccelerationJerkMean_Xaxis






####fBodyAccelerationJerkMean_Yaxis






####fBodyAccelerationJerkMean_Zaxis






####fBodyGyroMean_Xaxis






####fBodyGyroMean_Yaxis






####fBodyGyroMean_Zaxis






####fBodyAccelerationMagMean






####fBodyBodyAccelerationJerkMagMean







####fBodyBodyGyroMagMean






####fBodyBodyGyroJerkMagMean






####tBodyAccelerationStd_Xaxis






####tBodyAccelerationStd_Yaxis






####tBodyAccelerationStd_Zaxis






####tGravityAccelerationStd_Xaxis







####tGravityAccelerationStd_Yaxis






####tGravityAccelerationStd_Zaxis






####tBodyAccelerationJerkStd_Xaxis






####tBodyAccelerationJerkStd_Yaxis






####tBodyAccelerationJerkStd_Zaxis






####tBodyGyroStd_Xaxis






####tBodyGyroStd_Yaxis






####tBodyGyroStd_Zaxis






####tBodyGyroJerkStd_Xaxis







####tBodyGyroJerkStd_Yaxis







####tBodyGyroJerkStd_Zaxis







####tBodyAccelerationMagStd







####tGravityAccelerationMagStd







####tBodyAccelerationJerkMagStd







####tBodyGyroMagStd







####tBodyGyroJerkMagStd







####fBodyAccelerationStd_Xaxis







####fBodyAccelerationStd_Yaxis






####fBodyAccelerationStd_Zaxis







####fBodyAccelerationJerkStd_Xaxis






####fBodyAccelerationJerkStd_Yaxis






####fBodyAccelerationJerkStd_Zaxis






####fBodyGyroStd_Xaxis






####fBodyGyroStd_Yaxis






####fBodyGyroStd_Zaxis






####fBodyAccelerationMagStd






####fBodyBodyAccelerationJerkMagStd






####fBodyBodyGyroMagStd






####fBodyBodyGyroJerkMagStd
