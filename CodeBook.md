# Introduction

The script `run_analysis.R`performs the 5 steps as defined in the course project instructions.

* All similar data is merged with the rbind() function.
* Only columns with the mean and standard deviation measures are taken from the dataset. 
* The column name are assigned as defined in the features.txt file.
* Vague column names updated.
* New dataset is generated using the average measures for each activtivy type and subject
* Finally, we generate a new dataset with all the average measures for each subject and activity type (30 subjects * 6 activities = 180 rows). 

Output file: tidydata.txt

# Variables

* 'x_train', 'y_train', 'x_test', 'y_test', 'subject_train' and 'subject_test' are variables with data from the downloaded files.
* 'x_data', 'y_data' and 'subject_data'contains the merged datasets.
* 'features' contains the columns names for the 'x_data' dataset.
*  'activities' variable names updated.
* 'full_data' merges 'x_data', 'y_data' and 'subject_data' in a dataset.
* 'averages_data' contains the averages.