# [Python] Titanic-Machine-Learning-from-Disaster

## 1. Introduction

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this portfolio, my ultimate goal is to complete the analysis of what sorts of people were likely to survive. In particular, I will take the advantage of knowledge about data science and machine learning to apply the tools of machine learning to predict which passengers survived the tragedy.

#### Data Dictionary
|Variable|Description|Key
|:--|:----------------------------------------|:----------------------------------------|
|Survival |Survival|0 = No, 1 = Yes|
|pclass |  Ticket class |	1 = 1st, 2 = 2nd, 3 = 3rd |
|sex | Sex |	 |
|Age |Age in years |	 |
|sibsp |# of siblings / spouses aboard the Titanic	 |	 |
|parch |# of parents / children aboard the Titanic	 |	 |
|ticket | Ticket number	 |	 |
|fare	 | Passenger fare |	 |
|cabin | Cabin number	 |	 |
|embarked |Port of Embarkation		 |C = Cherbourg, Q = Queenstown, S = Southampton	 |

## 2. Method
These are the steps that I followed in this project:
#### Data Overview & Feature analysis
> - Showing descriptive statistics and feature distribution
> - Exploring the correaltion between features
> - Detecting the outliers
#### Data Preprocessing
> - Drop the unnecessary columns & the missing values
> - Data Transformation
> - Feature Engineering
> - Feature Encoding
#### Modelling
> - Exploring data
> - Building models : Logistic Regression and KNN model
> - Making predictions
> - Evaluating results. 
#### Tuning The Hyper-parameter 

## 3. Conclusion
1.  Answer the question  **What sort of people were likely to survive than others** are the passengers who have one of these features:
    - Young ages - especially children
    - Is a Female
    - Hold the first-class ticket
    - Have family members on the Titanic
    - Embarked from Cherbourg Port
    - Have a 'Master' title
    - The ticket's price is higher than `$32`
2. **Model Performance**:
    - The results of 3 models are **Logistic Regression** = `83.33%`, **KNN (K = 10)** = `88.89%`, **tunned KNN (K = 33)** = `87.78%`. The model with best performance is **KNN model** with `88.89%` accuracy. This means the **KNN model** can predict the survival possibility of a passenger at 88.89% accuracy.
3. **Possible extension can be done to improve the accuracy**:
    - Analyse ticket and cabin features
    - Come up with alternative features in feature engineering
    - Remove less important features



