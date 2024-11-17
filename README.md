## Project Overview

The Titanic dataset contains information about the passengers aboard the ill-fated Titanic ship, including their personal details (age, sex, class, etc.) and whether they survived or not. Through this EDA, we aim to understand the relationships between these features and the likelihood of survival.

## Dataset
The dataset used in this project is the famous Titanic dataset, available on Kaggle. It contains the following columns:

### PassengerId: Unique ID for each passenger
### Pclass: Ticket class (1st, 2nd, 3rd)
### Name: Name of the passenger
### Sex: Gender of the passenger
### Age: Age of the passenger
### SibSp: Number of siblings or spouses aboard the Titanic
### Parch: Number of parents or children aboard the Titanic
### Ticket: Ticket number
### Fare: Ticket fare
### Cabin: Cabin number
### Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
### Survived: Survival (0 = No, 1 = Yes)

## Conclusion


The exploratory data analysis (EDA) conducted on the Titanic dataset provided useful insights into the factors that could influence passenger survival. Here's a summary of the key conclusions from the analysis:

## Survival Distribution:

A significant portion of passengers did not survive the Titanic disaster, with approximately 62% of passengers being classified as non-survivors.
Gender Impact on Survival:

Gender was a significant factor in determining survival rates. Females had a much higher survival rate (about 74%) compared to males, whose survival rate was around 19%. This could be attributed to "women and children first" policies during the evacuation.

## Age Distribution:

Passengers in the age group of 0-10 years had a higher survival rate compared to older age groups. This aligns with the idea that children were prioritized in the evacuation process.
Class and Ticket Fare:

First-class passengers had the highest survival rates (around 62%), followed by second class (about 47%), and third class (approximately 24%). This suggests that those with more financial resources had a better chance of survival.

Higher ticket fares seemed to correlate with a higher likelihood of survival, further supporting the socio-economic influence on survival.

## Embarked Location:

Passengers who embarked at Cherbourg (C) had the highest survival rate (55%), followed by those who embarked in Southampton (S). The survival rate for passengers embarking in Queenstown (Q) was relatively low.

## Missing Data Handling:

We observed some missing values, particularly in the Age and Embarked columns. These were imputed with the median and mode values, respectively. The Sex column was initially problematic due to missing values, but after addressing this, it became a useful feature in predicting survival rates.