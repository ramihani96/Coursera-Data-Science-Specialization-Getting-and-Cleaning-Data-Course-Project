# Getting and Cleaning Data - Course-Project
* The included R script, __run_analysis.R__, conducts the following:</br>
1. Read both the train and test datasets and merge them into x(measurements), y(activity) and subject, respectively.</br>
2. Load the data(x's) feature, activity info and extract columns named 'mean'__(-mean)__ and 'standard deviation'__(-std)__. Also, modify column names to descriptive. __(-mean to Mean, -std to Std, and remove symbols like -, (, ))__</br>
3. Extract data by selected columns(from step 2), and merge x, y(activity) and subject data. Also, replace y(activity) column to it's name by refering activity label (loaded step 3).</br>
4. Generate __'Tidy Dataset'__ that consists of the average (mean) of each variable for each subject and each activity. The result is shown in the file __tidy_dataset.txt__.
