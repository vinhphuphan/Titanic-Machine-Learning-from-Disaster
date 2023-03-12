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

#### Variable Notes
`pclass`: A proxy for socio-economic status (SES)
<br>1st = Upper
<br>2nd = Middle
<br>3rd = Lower

`age`: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

`sibSp`: The dataset defines family relations in this way:
<br>Sibling = brother, sister, stepbrother, stepsister
<br>Spouse = husband, wife (mistresses and fiancés were ignored)

`parch`: The dataset defines family relations in this way:
<br>Parent = mother, father
<br>Child = daughter, son, stepdaughter, stepson
<br>Some children travelled only with a nanny, therefore parch=0 for them

## 2. Method
These are the steps that this project follow :
#### Data Overview & Feature analysis
> - Showing descriptive statistics and feature distribution
> - Exploring the correaltion between features
> - Detecting the outliers
#### Data Preprocessing
> - Drop the unnecessary columns & the missing values
> - Data Transformation
>> The Fare column has very high positive skewness. Therefore, we need to use the log() method to solve this issue.
> - Feature Engineering
> - Feature Encoding
#### Modelling
> - Exploring data
> - Building models
> - Making predictions
> - Evaluating results. 
#### Tuning The Hyper-parameter 


