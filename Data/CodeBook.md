# Code Book - Getting and Cleaning Data - module 4 - Peer-Graded Assignment

## Experimental Study Design

A description of how the data was collected:

- see the [raw data README](./raw-data-readme.md) (the original README)

## Code Book

### Processed Data - Merged with Means by Activity and Subject

- [merged_means-by-activity-and-subject.txt](./merged_means-by-activity-and-subject.txt)

1. The variables (including units) in the data set

Other variables (columns) have a naming convention:

- angle: Angle between two vectors.
- Time: accelerometer and gyroscope 3-axial raw signals in time domain. In the raw data, they were original captured at a constant rate of 50 Hz and then filtered for noise (see the raw readme).
- Jerk - A jerk signal, obtained in raw data from body linear acceleration and angular velocity.
- Fourier - the FFT (Fast Fourier Transform) domain signal.
- X|Y|Z Axis - The axis of the accelerometer or gyroscope.
- Body - the body record (in raw data, the gravity element was already subtracted)
- Accelerometer - the accerometer record
- Gravity - the gravity element
- mean_ prefix: to indicate this is a mean of the grouped variables (grouped by Subject, ActivityLabel).

Variables (columns):

- Record - A key to identify this record in this dataset.
- Subject - The ID of the subject.
- ActivityLabel - The label of the activity.
- mean_angle_Time_BodyAcceleration_Gravity - Mean angle in time domain, for body accelaration with gravity.
- mean_angle_Time_BodyAccelerationJerk_Gravity  - Mean angle in time domain, for body accelaration jerk with gravity.
- mean_angle_Time_BodyGyro_Gravity - Mean angle in time domain, for body gyro with gravity.
- mean_angle_Time_BodyGyroJerk_Gravity - Mean angle in time domain, for body gyro jerk, with gravity.
- mean_angle_XAxis_Gravity - Mean angle on X axis for gravity.
- mean_angle_YAxis_Gravity - Mean angle on Y axis for gravity.
- mean_angle_ZAxis_Gravity - Mean angle on Z axis for gravity.
- mean_Fourier_BodyAcceleration-Freq_XAxis - Mean of FFT (Fast Fourier Transform) of body accelaration frequency on X axis.
- mean_Fourier_BodyAcceleration-Freq_YAxis - Mean of FFT (Fast Fourier Transform) of body accelaration frequency on Y axis.
- mean_Fourier_BodyAcceleration-Freq_ZAxis - Mean of FFT (Fast Fourier Transform) of body accelaration frequency on Z axis.
- mean_Fourier_BodyAcceleration_XAxis - Mean of FFT (Fast Fourier Transform) of body accelaration on X axis.
- mean_Fourier_BodyAcceleration_YAxis - Mean of FFT (Fast Fourier Transform) of body accelaration on Y axis.
- mean_Fourier_BodyAcceleration_ZAxis - Mean of FFT (Fast Fourier Transform) of body accelaration on Z axis.
- mean_Fourier_BodyAccelerationJerk-Freq_XAxis - Mean of FFT (Fast Fourier Transform) of body accelaration jerk frequency on X axis.
- mean_Fourier_BodyAccelerationJerk-Freq_YAxis - Mean of FFT (Fast Fourier Transform) of body accelaration jerk frequency on Y axis.
- mean_Fourier_BodyAccelerationJerk-Freq_ZAxis - Mean of FFT (Fast Fourier Transform) of body accelaration jerk frequency on Z axis.
- mean_Fourier_BodyAccelerationJerk_XAxis - Mean of FFT (Fast Fourier Transform) of body accelaration jerk on X axis.
- mean_Fourier_BodyAccelerationJerk_YAxis - Mean of FFT (Fast Fourier Transform) of body accelaration jerk on Y axis.
- mean_Fourier_BodyAccelerationJerk_ZAxis - Mean of FFT (Fast Fourier Transform) of body accelaration jerk on Z axis.
- mean_Fourier_BodyAccelerationJerkMagnitude - Mean of FFT (Fast Fourier Transform) of body accelaration jerk magnitude.
- mean_Fourier_BodyAccelerationJerkMagnitude-Freq - Mean of FFT (Fast Fourier Transform) of body accelaration jerk magnitude frequency.
- mean_Fourier_BodyAccelerationMagnitude - Mean of FFT (Fast Fourier Transform) of body accelaration magnitude.
- mean_Fourier_BodyAccelerationMagnitude-Freq - Mean of FFT (Fast Fourier Transform) of body accelaration magnitude frequency.
- mean_Fourier_BodyGyro-Freq_XAxis - Mean of FFT (Fast Fourier Transform) of body gyro frequency - X axis.
- mean_Fourier_BodyGyro-Freq_YAxis - Mean of FFT (Fast Fourier Transform) of body gyro frequency - Y axis.
- mean_Fourier_BodyGyro-Freq_ZAxis - Mean of FFT (Fast Fourier Transform) of body gyro frequency - Z axis.
- mean_Fourier_BodyGyro_XAxis - Mean of FFT (Fast Fourier Transform) of body gyro - X axis.
- mean_Fourier_BodyGyro_YAxis - Mean of FFT (Fast Fourier Transform) of body gyro - Y axis.
- mean_Fourier_BodyGyro_ZAxis - Mean of FFT (Fast Fourier Transform) of body gyro - Z axis.
- mean_Fourier_BodyGyroJerkMagnitude - Mean of FFT (Fast Fourier Transform) of body gyro jerk magnitude.
- mean_Fourier_BodyGyroJerkMagnitude-Freq - Mean of FFT (Fast Fourier Transform) of body gyro jerk magnitude - frequency.
- mean_Fourier_BodyGyroMagnitude - Mean of FFT (Fast Fourier Transform) of body gyro magnitude.
- mean_Fourier_BodyGyroMagnitude-Freq - Mean of FFT (Fast Fourier Transform) of body gyro magnitude frequency.
- mean_Time_BodyAcceleration_XAxis - Mean in time domain, body accelaration - X axis.
- mean_Time_BodyAcceleration_YAxis - Mean in time domain, body accelaration - Y axis.
- mean_Time_BodyAcceleration_ZAxis - Mean in time domain, body accelaration - Z axis.
- mean_Time_BodyAccelerationJerk_XAxis - Mean in time domain, body accelaration jerk - X axis.
- mean_Time_BodyAccelerationJerk_YAxis - Mean in time domain, body accelaration jerk - Y axis.
- mean_Time_BodyAccelerationJerk_ZAxis - Mean in time domain, body accelaration jerk - Z axis.
- mean_Time_BodyAccelerationJerkMagnitude - Mean in time domain, body accelaration jerk magnitude.
- mean_Time_BodyAccelerationMagnitude - Mean in time domain, body accelaration magnitude.
- mean_Time_BodyGyro_XAxis - Mean in time domain, body gyro - X axis.
- mean_Time_BodyGyro_YAxis - Mean in time domain, body gyro - Y axis.
- mean_Time_BodyGyro_ZAxis - Mean in time domain, body gyro - Z axis.
- mean_Time_BodyGyroJerk_XAxis - Mean in time domain, body gyro jerk - X axis.
- mean_Time_BodyGyroJerk_YAxis - Mean in time domain, body gyro jerk - Y axis.
- mean_Time_BodyGyroJerk_ZAxis - Mean in time domain, body gyro jerk - Z axis.
- mean_Time_BodyGyroJerkMagnitude - Mean in time domain, body gyro jerk magnitude.
- mean_Time_BodyGyroMagnitude - Mean in time domain, body gyro magnitude.
- mean_Time_GravityAcceleration_XAxis - Mean in time domain, gravity accelaration - X axis.
- mean_Time_GravityAcceleration_YAxis - Mean in time domain, gravity accelaration - Y axis.
- mean_Time_GravityAcceleration_ZAxis - Mean in time domain, gravity accelaration - Z axis.
- mean_Time_GravityAccelerationMagnitude - Mean in time domain, gravity accelaration magnitude.

2. The summary choices made

- raw data was read from the test and train data sets
- the raw inertial signals were not included
- the variables were filtered down to: Y, contains("std"), contains("mean"), contains("Subject")
- the test and train data sets were merged
- the activity numbers were replaced with labels
- the columns were renamed to replace all abbreviations, and clean up characters like (,)
- a Record variable (an index) was added
- the columns were re-ordered ("Record","Subject","ActivityLabel" first, then alphabetically sorted)
- the data was grouped by (Subject, ActivityLabel), aggregating the other columns by taking their mean
- the new mean columns were renamed to have a mean_ prefix, for clarity
- saved as a table (.txt) file
