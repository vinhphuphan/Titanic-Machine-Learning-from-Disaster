<h1 align="center">Titanic - Machine Learning from Disaster using Python<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="55" height="40"</h1>

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
* <a href = "https://www.python.org/">Python</a> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="25" height="20"/> </a>

* <a href = "https://en.wikipedia.org/wiki/Statistics">Statistics</a> <img src="https://raw.githubusercontent.com/mrankitgupta/66DaysOfData/c8c040f1c85d921db317152567f331354446286a/statistics-21.svg" alt="Statistics" width="25" height="25"/> </a>

##### Python Libraries : 
* <a href="https://pandas.pydata.org/">Pandas</a><img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="25" height="20"/> </a> |  <a href="https://numpy.org/">NumPy</a><img src="https://raw.githubusercontent.com/mrankitgupta/mrankitgupta/2a582d085b324cff4917325112229027309ecae3/Numpy-logo.svg" alt="numpy" width="25" height="20"/> </a> |  <a href="https://matplotlib.org/">Matplotlib</a> <img src="https://raw.githubusercontent.com/mrankitgupta/mrankitgupta/1331979c3208a15be2c2a6177ffc38ced3d6b434/Matplotlib_icon.svg" alt="matplotlib" width="25" height="20"/> </a> |  <a href="https://seaborn.pydata.org">Seaborn</a><a href="https://seaborn.pydata.org" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="Seaborn" width="25" height="20"/> </a>| <a href="https://scikit-learn.org/stable/">Scikit-Learn</a><img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="Scikit-learn" width="25" height="20"/> </a>

### 3. Conclusion
1.  **Answer the question "What sort of people were likely to survive than others?"**<br>
    - passengers who are young ages - especially children
      <p align="center">
      <img width="50%" height="50%" src="https://github.com/vinhphuphan/Titanic-Machine-Learning-from-Disaster/blob/main/images/Age.png" alt="Titanic-Machine-Learning-from-Disaster using Python">
      </p>
    - Is a Female
      <p align="center">
      <img width="40%" height="40%" src="https://github.com/vinhphuphan/Titanic-Machine-Learning-from-Disaster/blob/main/images/Sex.jpg" alt="Titanic-Machine-Learning-from-Disaster using Python">
      </p>
    - Hold the first-class ticket and the ticket's price is higher than `$32`
      <p align="center">
      <img width="50%" height="50%" src="https://github.com/vinhphuphan/Titanic-Machine-Learning-from-Disaster/blob/main/images/Fare.png" alt="Titanic-Machine-Learning-from-Disaster using Python">
      </p>
    - Have family members on the Titanic
      <p align="center">
      <img width="80%" height="80%" src="https://github.com/vinhphuphan/Titanic-Machine-Learning-from-Disaster/blob/main/images/isAlone.png" alt="Titanic-Machine-Learning-from-Disaster using Python">
      </p>
    - Embarked from Cherbourg Port
       <p align="center">
      <img width="40%" height="40%" src="https://github.com/vinhphuphan/Titanic-Machine-Learning-from-Disaster/blob/main/images/Embarked.jpg" alt="Titanic-Machine-Learning-from-Disaster using Python">
      </p>
    - Have a 'Master' title
      <p align="center">
      <img width="70%" height="70%" src="https://github.com/vinhphuphan/Titanic-Machine-Learning-from-Disaster/blob/main/images/master.png" alt="Titanic-Machine-Learning-from-Disaster using Python">
      </p>
2. **Model Performance**:
    - The results of 3 models are **Logistic Regression** = `83.33%`, **KNN (K = 10)** = `88.89%`, **tunned KNN (K = 33)** = `87.78%`. The model with best performance is **KNN model** with `88.89%` accuracy. This means the **KNN model** can predict the survival possibility of a passenger at 88.89% accuracy.
      <p align="center">
      <img width="50%" height="50%" src="https://github.com/vinhphuphan/Titanic-Machine-Learning-from-Disaster/blob/main/images/Model_Compare.png" alt="Titanic-Machine-Learning-from-Disaster using Python">
      </p>
3. **Possible extension can be done to improve the accuracy**:
    - Analyse ticket and cabin features
    - Come up with alternative features in feature engineering
    - Remove less important features
  
## Related Projects:question: 👨‍💻 🛰️

**Data Analysis**

<code>[Olympic-Weightlifting-Data-Analysis Using R](https://github.com/vinhphuphan/Olympic-Weightlifting-Data-Analysis)</code> 📊

<code>[Australia Road Deaths Statistic Report Using Excel](https://github.com/vinhphuphan/Australia-Road-Deaths-Statistic)</code> 📊

<code>[Titanic - Machine Learning from Disaster using Python](https://github.com/vinhphuphan/Titanic-Machine-Learning-from-Disaster)</code> 📊

<code>[Australian Politicians Twitter Data Analysis Using Python](https://github.com/vinhphuphan/Tweets-Analysis)</code> 📊

**Data Science Applications**

<code>[Text Classification With Movie Reviews](https://github.com/vinhphuphan/Text-Classification-With-Movie-Reviews/)</code> 📊

<code>[Living Species Image Classification using Python](https://github.com/vinhphuphan/Living-Species-Image-Classification)</code> 📊

<code>[Name Entity Recognition](https://github.com/vinhphuphan/Name-Entity-Recognition)</code> 📊

**Website Front End Practice**

<code>[Hospital-Landing-Page](https://github.com/vinhphuphan/Hospital-Landing-Page/)</code> 📊

<code>[LaslesVPN Landing Page](https://github.com/vinhphuphan/Lasles-VPN-Landing-Page)</code> 📊

<code>[Frontend Mentor Challenge Submission Using HTML&CSS](https://github.com/vinhphuphan/Frontendmentor-Challenge-HTML-CSS)</code> 📊

**Have fun building!** 🚀

