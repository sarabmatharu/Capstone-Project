### Salary Prediction - Capstone Project

## Objective of the project
The goal of this machine learning project is to predict whether a person makes over 50K a year or not given their demographic information. To achieve this, several classification techniques are explored and the random forest model  and Random Forest And Radial Support Vector Machine yields to the best prediction result.

### Project Description:
The census is a special, wide-range activity. The purpose is to gather information about the general population, in order to present a full and reliable picture of the population in the country - its housing conditions and demographic, social and economic characteristics. The information collected includes data on age, gender, country of origin, marital status, housing conditions, marriage, education, employment, etc.

This information makes it possible to plan better services, improve the quality of life and solve existing problems. Statistical information, which serves as the basis for constructing planning forecasts, is essential for the democratic process.

The project involves: 

    1. Data Cleaning
    2. Preprocessing and feature engineering
    3. Data Analysis
    4. Modeling

Exploratory data analysis and pre-processing, import all required libraries and clean the data sets, analyze and visualize the relationships between the different variables, handle all N/As, and perform feature engineering as needed. After exploring data set we found out that there are some missing vales in the dataset. The best way for analysis of the dataset is in the graphical structure which in turn lets us know the range of the data. 

Random Forest And Radial Support Vector Machine are the most accurate models.

Reflection : 
* Education data was dropped as it was collinear with education number.
* Marital - Status Categories were clubbed into single related category.
* Interestingly chances of having salary greater than 50k is high.
* Most people are working 40 hours a week. Among those who work more than 40 hours a week, the proportion of people having >50k is high.
* Married people have more chances of having income >50k as compared to never married and divorced.
* Income is more for higher age group.
* Higher value of education number maximizes the chnace of income >50k.
* The highest chances of having income >50k are in : Prof-School, Doctorate, Masters, Beachelors & Assoc-Voc.


