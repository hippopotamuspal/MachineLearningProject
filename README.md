# MachineLearningProject

# Income Census Data

## Contributors Quinn Daley, Sanjana Prabhakar, Mackenzie Deets, and Conner Dekok

## Overview
This project focuses on analyzing census income data infomation for the year of 1994. The main question we looked at was wether or not a persons annual income was over or under $ 50,000. When viewing the data there was a variety of collumns such as age, workclass, education, marital status, occupation, relationship, race, sex. 

For this project we had to train a model with the goal to have an accuracy total of over 75%.

### Repo Path and HTML 
Link to repository: https://github.com/hippopotamuspal/MachineLearningProject 


### Step-by-Step Process-
1. Data Import and Initial Cleaning:
We imported out data through a csv file.  There were various values such as "?" and replaced them to become "Unknown". We also had to strip and lower the values to help clean the values if they had any leading or spaces towards the end.  

We also had to filer out values in the "Workclass" column labeled as "never-worked" and "without-pay".  This was done through the isin function.

Also having to drop multiple columns from our dataframe such as "Education", "Capital Gain", and "capital loss".  And renaming the "EducationNum" column to "Education Rank". 

2. The file was ran through google collab with the adult.csv file having to be imported into collab for the script to run properly. 
 
3. There were various values such as "?" and replaced them to become "Unknown". We also had to strip and lower the values to help clean the values if they had any leading or spaces towards the end.  

4. 

5. 


6. Reading Data into Pyspark: 
The cleaned data set had our target values of income being over or under $50,000 resulting in a value of 0 being under 50,000, and 1 being over 50,000.  Then read the dataset into Pyspark and converted the pandas dataframe into a Pyspark dataframe.

Also ecoded all of the varibles with get_dummies to get the whole dataframe into values of 0 or 1 of those values that weren't numerical orginally. 

Then we extracted the income column to a seperate dataframe. Then further converted the Pyspark datafram back into Pandas. 

 
7.
 
8. 
9. Models used to view the accuracy: 
Linear Regression Model,
KNN, 
Random Forest 

10. 
 

  
  

### Key Learnings-


### Conclusion-
  
### Presentation-

Link to slides: https://www.canva.com/design/DAGYefdtCZM/nLaOspHxI0nWZ0vJPAlktw/edit?utm_content=DAGYefdtCZM&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton 



### Data Ethics- 


### Credit and Sources- 

Dataset: https://www.kaggle.com/datasets/tawfikelmetwally/census-income-dataset

The dataset had a a test csv along with a full csv.

For our project we used the full csv titled "adult.csv".




