# MachineLearningProject

# Income Census Data

## Contributors Quinn Daley, Sanjana Prabhakar, Mackenzie Deets, and Conner Dekok

## Overview
This project utilizes 1994 census data to predict whether an individual's income exceeds $50,000 based on set demographic and professional data. The dataset included features like as age, education, marital status, occupation, and race. Our objective was to optimize machine learning models to achieve high predictive performance in who did and who did not make more than $50,000 in 1994 based upon these features.For this project, we primarily focused on training at least one of our three models to have an accuracy total of over 75%.

### Repo Path and HTML 
Link to repository: https://github.com/hippopotamuspal/MachineLearningProject 


### Data Model Implementation

1. Data Import and Cleaning:
    - Data is retrieved from datasets/adult.csv and processed using Pandas and SQL.
    - Columns such as Education, Capital Gain, and Capital Loss were removed for irrelevance.
    - Null values were replaced, and categorical data was one-hot encoded.
    - Numerical columns were normalized and standardized to improve model performance.
1. PySpark Incorporation:
    - Data preprocessing included PySpark queries to separate our target column from the rest of the dataset to prepare our data for fitting.
1. Model Training and Evaluation:
    - A Logistic Regression model was implemented and compared with K-Nearest Neighbors (KNN) and Random Forest models.
    - Highest Yields
    - Logistic Regression & Random Forest achieved 84% accuracy
    - KNN delivered competitive but slightly lower performance (~78%).

### Data Model Optimization
- Iterative tuning included adjustments to hyperparameters such as the number of neighbors in KNN, depth in Random Forest, and regularization in Logistic Regression.
- Performance metrics (accuracy, precision, recall, and F1-score) were recorded at each iteration and displayed in the script for clarity.
- The optimized Random Forest model with hyperparameters such as 2000 estimators and a maximum depth of 15 demonstrated the best performance.

### Conclusion-

We achieved moderately successful results with our project. The Logistic Regression model reached an accuracy of 84%, K-Nearest Neighbors achieved 78%, and the optimized Random Forest model delivered accuaracy like the logitic regression of 84.3%. Iterative tuning of hyperparameters improved performance especially in the Random Forest model. We feel that these results highlight how important it is to choose an effective model and how important optimization can be in iteratively developing more and more meaningful predictions.

### Presentation-

Link to slides: https://www.canva.com/design/DAGYefdtCZM/nLaOspHxI0nWZ0vJPAlktw/edit?utm_content=DAGYefdtCZM&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton 


### Data Ethics- 

This project involves pretty sensitive socioeconomic data and needed some more careful attention to our data ethics. For example, the dataset includes demographic features such as race, sex, and marital status. All of these could introduce biases, and luckily, our models natively should make sure its predictions don't favor groups by analyzing performance metrics across many demographics. The publicly available dataset is also anonymous and does not reveal personal identifying information.

### Credit, Sources and References- 

Dataset: https://www.kaggle.com/datasets/tawfikelmetwally/census-income-dataset

The dataset had a a test csv along with a full csv.

For our project we used the full csv titled "adult.csv".

References: Prior assignments and chatgpt were used to help create models. 




