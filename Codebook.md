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

These signals were used to estimate variables of the 561 variable feature vector.Features are normalized and bounded within [-1,1].


===================================================================

The Tidy data set that is returned by the run_analysis.R extracts a subset of the above mentioned measurements.
Variables which are mean and StandardDeviation of the measurements are included in the dataset.
Each record in the tidy dataset are average of each variable for each activity and each subject. 

===================================================================
###Following are the description of the column fields(variables) of the dataset.



####Subject_Id

* Variable Index = 1
* Class Of Variable = Integer
* Variable Details = Id of the Volunteer who carried out the experiment. 
* Range Of Values = 1 to 30

####Activity_Label

* Variable Index = 2
* Class Of Variable = Character
* Variable Details = Name of the  carried out the experiment. 
* Range Of Values =  WALKING , WALKING_UPSTAIRS , WALKING_DOWNSTAIRS , SITTING , STANDING , LAYING

####tBodyAccelerationMean_Xaxis

* Variable Index = 3
* Class Of Variable = Numeric
* Variable Details = Mean of Body Acceleration in time domain along X-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 0.22159824394 to 0.3014610196

####tBodyAccelerationMean_Yaxis

* Variable Index = 4
* Class Of Variable = Numeric
* Variable Details = Mean of Body Acceleration in time domain along Y-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = -0.040513953 to -0.00130828

####tBodyAccelerationMean_Zaxis

* Variable Index = 5
* Class Of Variable = Numeric
* Variable Details = Mean of Body Acceleration in time domain along Z-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = -0.1525138995 to -0.075378468

####tGravityAccelerationMean_Xaxis

* Variable Index = 5
* Class Of Variable = Numeric
* Variable Details = Mean of Gravity Acceleration in time domain along X-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = -0.680043155 to 0.974508732

####tGravityAccelerationMean_Yaxis

* Variable Index = 6
* Class Of Variable = Numeric
* Variable Details = Mean of Gravity Acceleration in time domain along Y-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tGravityAccelerationMean_Zaxis

* Variable Index = 7
* Class Of Variable = Numeric
* Variable Details = Mean of Gravity Acceleration in time domain along Z-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tBodyAccelerationJerkMean_Xaxis

* Variable Index = 8
* Class Of Variable = Numeric
* Variable Details = Mean of Body Jerk Acceleration in time domain along X-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tBodyAccelerationJerkMean_Yaxis

* Variable Index = 9
* Class Of Variable = Numeric
* Variable Details = Mean of Body Jerk Acceleration in time domain along Y-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tBodyAccelerationJerkMean_Zaxis


* Variable Index = 10
* Class Of Variable = Numeric
* Variable Details = Mean of Body Jerk Acceleration in time domain along Z-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tBodyGyroMean_Xaxis

* Variable Index = 11
* Class Of Variable = Numeric
* Variable Details = Mean of Body angular velocity(data from gyroscope) in time domain along X-axis
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1

####tBodyGyroMean_Yaxis

* Variable Index = 12
* Class Of Variable = Numeric
* Variable Details = Mean of Body angular velocity(data from gyroscope) in time domain along Y-axis
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1

####tBodyGyroMean_Zaxis

* Variable Index = 13
* Class Of Variable = Numeric
* Variable Details = Mean of Body angular velocity(data from gyroscope) in time domain along Z-axis
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1

####tBodyGyroJerkMean_Xaxis

* Variable Index = 14
* Class Of Variable = Numeric
* Variable Details = Mean of Body Jerk angular velocity(data from gyroscope) in time domain along X-axis
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1

####tBodyGyroJerkMean_Yaxis

* Variable Index = 15
* Class Of Variable = Numeric
* Variable Details = Mean of Body Jerk angular velocity(data from gyroscope) in time domain along Y-axis
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1

####tBodyGyroJerkMean_Zaxis

* Variable Index = 16
* Class Of Variable = Numeric
* Variable Details = Mean of Body Jerk angular velocity(data from gyroscope) in time domain along Z-axis
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1


####tBodyAccelerationMagMean

* Variable Index = 17
* Class Of Variable = Numeric
* Variable Details = Mean of Magnitude of Body Acceleration in time domain
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tGravityAccelerationMagMean

* Variable Index = 18
* Class Of Variable = Numeric
* Variable Details = Mean of Magnitude of Gravity Acceleration in time domain
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tBodyAccelerationJerkMagMean

* Variable Index = 19
* Class Of Variable = Numeric
* Variable Details = Mean of Magnitude of Body Jerk Acceleration in time domain
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tBodyGyroMagMean

* Variable Index = 21
* Class Of Variable = Numeric
* Variable Details = Mean of Magnitude of Body angular velocity(data from gyroscope) in time domain
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1

####tBodyGyroJerkMagMean

* Variable Index = 22
* Class Of Variable = Numeric
* Variable Details = Mean of Magnitude of Body Jerk angular velocity(data from gyroscope) in time domain
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1

####fBodyAccelerationMean_Xaxis

* Variable Index = 23
* Class Of Variable = Numeric
* Variable Details = Mean of Body Acceleration in frequency domain along X-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyAccelerationMean_Yaxis

* Variable Index = 24
* Class Of Variable = Numeric
* Variable Details = Mean of Body Acceleration in frequency domain along Y-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyAccelerationMean_Zaxis

* Variable Index = 25
* Class Of Variable = Numeric
* Variable Details = Mean of Body Acceleration in frequency domain along Z-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1


####fBodyAccelerationJerkMean_Xaxis

* Variable Index = 26
* Class Of Variable = Numeric
* Variable Details = Mean of Body Jerk Acceleration in frequency domain along X-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyAccelerationJerkMean_Yaxis

* Variable Index = 27
* Class Of Variable = Numeric
* Variable Details = Mean of Body Jerk Acceleration in frequency domain along Y-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyAccelerationJerkMean_Zaxis

* Variable Index = 28
* Class Of Variable = Numeric
* Variable Details = Mean of Body Jerk Acceleration in frequency domain along Z-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyGyroMean_Xaxis

* Variable Index = 29
* Class Of Variable = Numeric
* Variable Details = Mean of Body angular velocity(data from gyroscope) in frequency domain along X-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyGyroMean_Yaxis

* Variable Index = 30
* Class Of Variable = Numeric
* Variable Details = Mean of Body angular velocity(data from gyroscope) in frequency domain along Y-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyGyroMean_Zaxis

* Variable Index = 31
* Class Of Variable = Numeric
* Variable Details = Mean of Body angular velocity(data from gyroscope) in frequency domain along Z-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1


####fBodyAccelerationMagMean

* Variable Index = 32
* Class Of Variable = Numeric
* Variable Details = Mean of Magnitude of Body Acceleration in frequency domain
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1


####fBodyAccelerationJerkMagMean

* Variable Index = 33
* Class Of Variable = Numeric
* Variable Details = Mean of Magnitude of Body Jerk Acceleration in frequency domain
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyGyroMagMean

* Variable Index = 34
* Class Of Variable = Numeric
* Variable Details = Mean of Magnitude of Body angular velocity(data from gyroscope) in frequency domain
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyGyroJerkMagMean

* Variable Index = 35
* Class Of Variable = Numeric
* Variable Details = Mean of Magnitude of Body Jerk angular velocity(data from gyroscope) in frequency domain
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1


####tBodyAccelerationStd_Xaxis

* Variable Index = 36
* Class Of Variable = Numeric
* Variable Details = Standard Deviation of Body Acceleration in time domain along X-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 0.22159824394 to 0.3014610196

####tBodyAccelerationStd_Yaxis

* Variable Index = 37
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body Acceleration in time domain along Y-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = -0.040513953 to -0.00130828

####tBodyAccelerationStd_Zaxis

* Variable Index = 38
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body Acceleration in time domain along Z-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = -0.1525138995 to -0.075378468

####tGravityAccelerationStd_Xaxis

* Variable Index = 39
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Gravity Acceleration in time domain along X-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = -0.680043155 to 0.974508732

####tGravityAccelerationStd_Yaxis

* Variable Index = 40
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Gravity Acceleration in time domain along Y-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tGravityAccelerationStd_Zaxis

* Variable Index = 41
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Gravity Acceleration in time domain along Z-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tBodyAccelerationJerkStd_Xaxis

* Variable Index = 42
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body Jerk Acceleration in time domain along X-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tBodyAccelerationJerkStd_Yaxis

* Variable Index = 43
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body Jerk Acceleration in time domain along Y-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tBodyAccelerationJerkStd_Zaxis


* Variable Index = 44
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body Jerk Acceleration in time domain along Z-axis
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tBodyGyroStd_Xaxis

* Variable Index = 45
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body angular velocity(data from gyroscope) in time domain along X-axis
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1

####tBodyGyroStd_Yaxis

* Variable Index = 46
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body angular velocity(data from gyroscope) in time domain along Y-axis
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1

####tBodyGyroStd_Zaxis

* Variable Index = 47
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body angular velocity(data from gyroscope) in time domain along Z-axis
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1

####tBodyGyroJerkStd_Xaxis

* Variable Index = 48
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body Jerk angular velocity(data from gyroscope) in time domain along X-axis
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1

####tBodyGyroJerkStd_Yaxis

* Variable Index = 49
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body Jerk angular velocity(data from gyroscope) in time domain along Y-axis
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1

####tBodyGyroJerkStd_Zaxis

* Variable Index = 50
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body Jerk angular velocity(data from gyroscope) in time domain along Z-axis
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1


####tBodyAccelerationMagStd

* Variable Index = 51
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Magnitude of Body Acceleration in time domain
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tGravityAccelerationMagStd

* Variable Index = 52
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Magnitude of Gravity Acceleration in time domain
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tBodyAccelerationJerkMagStd

* Variable Index = 53
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Magnitude of Body Jerk Acceleration in time domain
* Variable Unit =  metre per second square(unit of g)
* Range Of Values = 1 to 1

####tBodyGyroMagStd

* Variable Index = 54
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Magnitude of Body angular velocity(data from gyroscope) in time domain
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1

####tBodyGyroJerkMagStd

* Variable Index = 55
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Magnitude of Body Jerk angular velocity(data from gyroscope) in time domain
* Variable Unit =  rad per second(rad/s)
* Range Of Values = 1 to 1

####fBodyAccelerationStd_Xaxis

* Variable Index = 56
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body Acceleration in frequency domain along X-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyAccelerationStd_Yaxis

* Variable Index = 57
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body Acceleration in frequency domain along Y-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyAccelerationStd_Zaxis

* Variable Index = 58
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body Acceleration in frequency domain along Z-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1


####fBodyAccelerationJerkStd_Xaxis

* Variable Index = 59
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body Jerk Acceleration in frequency domain along X-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyAccelerationJerkStd_Yaxis

* Variable Index = 60
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body Jerk Acceleration in frequency domain along Y-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyAccelerationJerkStd_Zaxis

* Variable Index = 61
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body Jerk Acceleration in frequency domain along Z-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyGyroStd_Xaxis

* Variable Index = 62
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body angular velocity(data from gyroscope) in frequency domain along X-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyGyroStd_Yaxis

* Variable Index = 63
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body angular velocity(data from gyroscope) in frequency domain along Y-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyGyroStd_Zaxis

* Variable Index = 64
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Body angular velocity(data from gyroscope) in frequency domain along Z-axis
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1


####fBodyAccelerationMagStd

* Variable Index = 65
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Magnitude of Body Acceleration in frequency domain
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1


####fBodyAccelerationJerkMagStd

* Variable Index = 66
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Magnitude of Body Jerk Acceleration in frequency domain
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyGyroMagStd

* Variable Index = 67
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Magnitude of Body angular velocity(data from gyroscope) in frequency domain
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1

####fBodyGyroJerkMagStd

* Variable Index = 68
* Class Of Variable = Numeric
* Variable Details = Standard deviation of Magnitude of Body Jerk angular velocity(data from gyroscope) in frequency domain
* Variable Unit =  Hertz (Hz)
* Range Of Values = 1 to 1
