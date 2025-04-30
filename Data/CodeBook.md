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
- Fourier (FastFourierTransform) - the FFT domain signal.
- X|Y|Z Axis - The axis of the accelerometer or gyroscope.
- Body - the body record (in raw data, the gravity element was already subtracted)
- Accelerometer - the accerometer record
- Gravity - the gravity element
- mean_ prefix: to indicate this is a mean of the grouped variables (grouped by Subject, ActivityLabel).

Variables (columns):

- "Record" - The record ID
- "Subject" - The subject ID
- "ActivityLabel" - The activity label


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
