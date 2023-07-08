<h1 align="center"> <a href="https://open.spotify.com/user/exll9wa5yql2llqyi1k5h56qm?si=YkkYuaD7SN60DMjXWo7eTQ&utm_source=copy-link" target="_blank"></a> Titanic-Machine-Learning-from-Disaster using Python <a href="https://github.com/mrankitgupta/PythonLessons" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="55" height="40"/> </a> </h1>

<p align="center">
  <img width="600" height="200" src="https://github.com/vinhphuphan/Titanic-Machine-Learning-from-Disaster/blob/main/images/Titanic.png">
</p>

### 1. Introduction

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

**In this project, my ultimate goal is to complete the analysis of what sorts of people were likely to survive. In particular, I will take the advantage of knowledge about data science and machine learning to apply the tools of machine learning to predict which passengers survived the tragedy.**

### 2. Method

These are the steps that I followed in this project:
- **Data Overview & Feature analysis** involves examining descriptive statistics, feature distributions, and correlations to gain insights into the data's characteristics and identify potential outliers.

- **Data Preprocessing** focuses on preparing the data for modeling by removing unnecessary columns and missing values, performing transformations and engineering features, and encoding categorical variables.

- **Modelling** encompasses exploring the data, building models such as Logistic Regression and KNN, making predictions using the trained models, and evaluating their performance to assess the effectiveness of the chosen approaches.

#### Technologies used ⚙️
* <a href="https://github.com/mrankitgupta/Python-Lessons">Python</a> <a href="https://github.com/mrankitgupta/Python-Lessons" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="25" height="20"/> </a>

* <a href="https://github.com/mrankitgupta/Statistics-for-Data-Science-using-Python">Statistics</a><a href="https://github.com/mrankitgupta/Statistics-for-Data-Science-using-Python" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/mrankitgupta/66DaysOfData/c8c040f1c85d921db317152567f331354446286a/statistics-21.svg" alt="Statistics" width="25" height="25"/> </a>

##### Python Libraries : 
* <a href="https://github.com/mrankitgupta/Kaggle-Pandas-Solved-Exercises">Pandas</a><a href="https://github.com/mrankitgupta/Kaggle-Pandas-Solved-Exercises" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="25" height="20"/> </a> |  <a href="https://numpy.org/">NumPy</a><a href="https://numpy.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/mrankitgupta/mrankitgupta/2a582d085b324cff4917325112229027309ecae3/Numpy-logo.svg" alt="numpy" width="25" height="20"/> </a> |  <a href="https://matplotlib.org/">Matplotlib</a><a href="https://matplotlib.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/mrankitgupta/mrankitgupta/1331979c3208a15be2c2a6177ffc38ced3d6b434/Matplotlib_icon.svg" alt="matplotlib" width="25" height="20"/> </a> |  <a href="https://seaborn.pydata.org">Seaborn</a><a href="https://seaborn.pydata.org" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="Seaborn" width="25" height="20"/> </a>| <a href="https://scikit-learn.org/stable/">Scikit-Learn</a><a href="https://scikit-learn.org/stable/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="Scikit-learn" width="25" height="20"/> </a>

## 3. Conclusion
1.  **Answer the question "What sort of people were likely to survive than others?"**<br>
    - passengers who are young ages - especially children
      <p align="center">
      <img width="50%" height="50%" src="https://github.com/vinhphuphan/Titanic-Machine-Learning-from-Disaster/blob/main/images/Age.png" alt="Titanic-Machine-Learning-from-Disaster using Python">
      </p>
    - Is a Female
      <p align="center">
      <img width="50%" height="50%" src="https://github.com/vinhphuphan/Titanic-Machine-Learning-from-Disaster/blob/main/images/Sex.png" alt="Titanic-Machine-Learning-from-Disaster using Python">
      </p>
    - Hold the first-class ticket
      <p align="center">
      <img width="50%" height="50%" src="https://github.com/vinhphuphan/Titanic-Machine-Learning-from-Disaster/blob/main/images/Fare.png" alt="Titanic-Machine-Learning-from-Disaster using Python">
      </p>
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



