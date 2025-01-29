# BSAN_6070_CA_01_Exploratory_Data_Analysis

##Installation Requirements
###This program needs to have the have the access to the following libraries:
-Numpy
-Pandas
-Matplotlib
-Seaborn
###If you are running this program on Google Colab, you should be fine as long as you are importing the libraries at the beginning (no installation necessary).

##Steps to Run the Code
-Open the code using Google Colab
-Make sure the GitHub links in the read_csv functions for the df variables is working (if not download the training and test files and then replace the GitHub link with the file path)
-Make sure you only have one df variable active at a time (either the training file or the test file) depending on what you are trying to do.
-Feel free to run the rest of the code

##Brief Narrative of the Code
###Part 1: Data Exploration and Analysis
####This part of the code will include various visualization of the variable analysis and the Data Quality Report that helps identify the data problems that exist in this dataset. These potential data problems include, missing data, outliers, and more. 

###Part 2: Data Cleaning and Correction
####After finding the issues in the first section, this part of the code helps fix the errors by minimizing the number of columns in the dataset based on the relevance to the task at hand and missing data. Then, we removed certain records with low percentage of missing data within specific columns. Finally, we are using certain methods to calculate and handle any outliers within the numberical values of the dataset.

###Part 3: Collinearity Visualization
#### In this section, we will use the narrowed down dataset to see if there is any collinearity present within the dataset through the creation of a heatmap. Based on the heatmap, we will need to see if there is any more columns that we need to remove. 
