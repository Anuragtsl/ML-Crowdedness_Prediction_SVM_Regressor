# ML-Crowdedness_Prediction_SVM_Regressor

I have created Machine Learning Model With SVM Regressor for Crowdedness Prediction.

In this I've used Python’s Famous libraries like [Numpy](https://numpy.org/), [Pandas](https://pandas.pydata.org/), [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/), and [Sklearn](https://scikit-learn.org/) for Analysis, Vizualization and Model Development.

I've used [Jupyter Notebook](https://jupyter.org/) for coding!

**Download the dataset from [here](https://github.com/Anuragtsl/ML-Crowdedness_Prediction_SVM_Regressor/blob/main/data.csv)!**

# Goals

Given a time of day (and maybe some other features, including weather), predict how crowded the gym will be.
Figure out which features are actually important, which are redundant, and what features could be added to make the predictions more accurate.

# Data

The dataset consists of 26,000 people counts (about every 10 minutes) over the last year. In addition, I gathered extra info including weather and semester-specific information that might affect how crowded it is. The label is the number of people, which I'd like to predict given some subset of the features.

**Label:**

* Number of people

**Features:**

* date (string; datetime of data)
* timestamp (int; number of seconds since beginning of day)
* dayofweek (int; 0 [monday] - 6 [sunday])
* is_weekend (int; 0 or 1) [boolean, if 1, it's either saturday or sunday, otherwise 0]
* is_holiday (int; 0 or 1) [boolean, if 1 it's a federal holiday, 0 otherwise]
* temperature (float; degrees fahrenheit)
* isstartof_semester (int; 0 or 1) [boolean, if 1 it's the beginning of a school semester, 0 otherwise]
* month (int; 1 [jan] - 12 [dec])
* hour (int; 0 - 23)

***Follow [notebook](https://github.com/Anuragtsl/ML-Crowdedness_Prediction_SVM_Regressor/blob/main/Crowdedness%20Prediction%20SVM%20Regressor.ipynb) for more!!***

# Preview

![Image1](https://github.com/Anuragtsl/ML-Crowdedness_Prediction_SVM_Regressor/blob/main/Images/1.png)

![Image2](https://github.com/Anuragtsl/ML-Crowdedness_Prediction_SVM_Regressor/blob/main/Images/2.png)


#Njoy!
