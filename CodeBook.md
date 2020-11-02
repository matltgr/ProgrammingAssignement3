# Code Book

# `tidy_set.txt` contents

Variables within the tidy dataset are the following:
- `Subject` - no unit - the subject of the following observation
- `Activity` - no unit - the activity performed by the subject
- ` tBodyAcc-mean()-X ` - original units - see original dataset
- ` tBodyAcc-mean()-Y ` - original units - see original dataset
- ` tBodyAcc-mean()-Z ` - original units - see original dataset
- ` tBodyAcc-std()-X ` - original units - see original dataset
- ` tBodyAcc-std()-Y ` - original units - see original dataset
- ` tBodyAcc-std()-Z ` - original units - see original dataset
- ` tGravityAcc-mean()-X ` - original units - see original dataset
- ` tGravityAcc-mean()-Y ` - original units - see original dataset
- ` tGravityAcc-mean()-Z ` - original units - see original dataset
- ` tGravityAcc-std()-X ` - original units - see original dataset
- ` tGravityAcc-std()-Y ` - original units - see original dataset
- ` tGravityAcc-std()-Z ` - original units - see original dataset
- ` tBodyAccJerk-mean()-X ` - original units - see original dataset
- ` tBodyAccJerk-mean()-Y ` - original units - see original dataset
- ` tBodyAccJerk-mean()-Z ` - original units - see original dataset
- ` tBodyAccJerk-std()-X ` - original units - see original dataset
- ` tBodyAccJerk-std()-Y ` - original units - see original dataset
- ` tBodyAccJerk-std()-Z ` - original units - see original dataset
- ` tBodyGyro-mean()-X ` - original units - see original dataset
- ` tBodyGyro-mean()-Y ` - original units - see original dataset
- ` tBodyGyro-mean()-Z ` - original units - see original dataset
- ` tBodyGyro-std()-X ` - original units - see original dataset
- ` tBodyGyro-std()-Y ` - original units - see original dataset
- ` tBodyGyro-std()-Z ` - original units - see original dataset
- ` tBodyGyroJerk-mean()-X ` - original units - see original dataset
- ` tBodyGyroJerk-mean()-Y ` - original units - see original dataset
- ` tBodyGyroJerk-mean()-Z ` - original units - see original dataset
- ` tBodyGyroJerk-std()-X ` - original units - see original dataset
- ` tBodyGyroJerk-std()-Y ` - original units - see original dataset
- ` tBodyGyroJerk-std()-Z ` - original units - see original dataset
- ` tBodyAccMag-mean() ` - original units - see original dataset
- ` tBodyAccMag-std() ` - original units - see original dataset
- ` tGravityAccMag-mean() ` - original units - see original dataset
- ` tGravityAccMag-std() ` - original units - see original dataset
- ` tBodyAccJerkMag-mean() ` - original units - see original dataset
- ` tBodyAccJerkMag-std() ` - original units - see original dataset
- ` tBodyGyroMag-mean() ` - original units - see original dataset
- ` tBodyGyroMag-std() ` - original units - see original dataset
- ` tBodyGyroJerkMag-mean() ` - original units - see original dataset
- ` tBodyGyroJerkMag-std() ` - original units - see original dataset
- ` fBodyAcc-mean()-X ` - original units - see original dataset
- ` fBodyAcc-mean()-Y ` - original units - see original dataset
- ` fBodyAcc-mean()-Z ` - original units - see original dataset
- ` fBodyAcc-std()-X ` - original units - see original dataset
- ` fBodyAcc-std()-Y ` - original units - see original dataset
- ` fBodyAcc-std()-Z ` - original units - see original dataset
- ` fBodyAccJerk-mean()-X ` - original units - see original dataset
- ` fBodyAccJerk-mean()-Y ` - original units - see original dataset
- ` fBodyAccJerk-mean()-Z ` - original units - see original dataset
- ` fBodyAccJerk-std()-X ` - original units - see original dataset
- ` fBodyAccJerk-std()-Y ` - original units - see original dataset
- ` fBodyAccJerk-std()-Z ` - original units - see original dataset
- ` fBodyGyro-mean()-X ` - original units - see original dataset
- ` fBodyGyro-mean()-Y ` - original units - see original dataset
- ` fBodyGyro-mean()-Z ` - original units - see original dataset
- ` fBodyGyro-std()-X ` - original units - see original dataset
- ` fBodyGyro-std()-Y ` - original units - see original dataset
- ` fBodyGyro-std()-Z ` - original units - see original dataset
- ` fBodyAccMag-mean() ` - original units - see original dataset
- ` fBodyAccMag-std() ` - original units - see original dataset
- ` fBodyBodyAccJerkMag-mean() ` - original units - see original dataset
- ` fBodyBodyAccJerkMag-std() ` - original units - see original dataset
- ` fBodyBodyGyroMag-mean() ` - original units - see original dataset
- ` fBodyBodyGyroMag-std() ` - original units - see original dataset
- ` fBodyBodyGyroJerkMag-mean() ` - original units - see original dataset
- ` fBodyBodyGyroJerkMag-std() ` - original units - see original dataset

# `run_analysis.R` notable variables

- `activities` - list of the activities possibles
- `agg_set` - tidy set generated by aggregation of `final_set`
- `features` - variables table
- `final_set` - tidy set at the end of step 4
- `merged_sbj_data` - merged data for the subjects
- `merged_x_data` - merged data for the `x` field
- `merged_y_data` - merged data for the `y` field
- `stats_x_data` - data extracted from `merged_x_data` corresponding to `mean()` or `std()` variables
- `features` - variable names extracted from `features` corresponding to `mean()` or `std()` variables
- `y_names` - merged table using activities names and `merged_y_data`