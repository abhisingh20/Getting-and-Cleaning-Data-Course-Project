The tidy_data.txt file is the tide data file which you can read in R which the read.table("tidy.txt") command.

Dimension of the table is 181 by 81

The first column is the subject
The second column shows the activity 
Rest of the columns show the accelerometer and gyroscope data

How the data are transformed by the script:
Data is read and preprocessed
I define the wanted features, concentrating on standard deviations and means.
Only the data relevant for the standard deviations and means are read in to memory.
Perform steps 1-3 for the test and the training set.
Transform activity names into factors.
Reshape the data so that subjects and activities become a variables of two independent columns.
Finally save the data.
