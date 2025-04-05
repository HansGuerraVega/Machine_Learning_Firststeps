# Project Description
Mobile company Megaline is dissatisfied with the fact that many of its customers are using legacy plans. They want to develop a model that can analyze customer behavior and recommend one of Megaline's new plans: Smart or Ultra.

You have access to behavioral data from subscribers who have already switched to the new plans. For this classification task, you must create a model that chooses the correct plan.
Develop a model with the highest possible accuracy. In this project, the accuracy threshold is 0.75. Use the dataset to check accuracy.

## Project Instructions
Open and examine the data file. File path: users_behavior.csv.
Segment the source data into a training set, a validation set, and a test set.
Investigate the quality of different models by changing the hyperparameters. Briefly describe the study's findings.
Check the quality of the model using the test set.
Additional task: Sanity test the model. This data is more complex than what you've used before, so it won't be an easy task.

## Data Description
Each observation in the dataset contains monthly behavior information about a user. The information provided is as follows:
calls — number of calls,
minutes — total call duration in minutes,
messages — number of text messages,
mb_used — Internet traffic used in MB,
is_ultra — plan for the current month (Ultra — 1, Smart — 0).
