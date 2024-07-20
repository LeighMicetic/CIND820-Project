# Abstract

As the average life expectancy for the United States of America continues to increase year over year (from 68.14 years in 1950 to 79.25 years in 2024)(United Nations), an increasing worry for some individuals is what factors contribute to living healthily as we age.   The purpose of this study is to build a predictive model to determine if an individual is aging healthily based on a series of health-related questions.  

## Research Question

Can the number of doctors an individual visits be predicted from questions related to sleeping habits, ratings of physical, dental and mental health, race and gender?

### Dataset

The dataset that will be used for this project was taken from the National Poll on Healthy Aging dataset that was funded by American Association of Retired People (AARP) and Michigan Medicine, the University of Michigan’s academic medical centre. This dataset was previously used by Malani, Preeti N., Jullgren, Jeffrey, and Solway, Erica in 2017.  As the dataset was previously used, missing values have been removed and the original variables have been filtered to the below.  The dataset relied on self-reported measurements from the targeted group. 

Repository URL: http://archive.ics.uci.edu/dataset/936/national+poll+on+healthy+aging+(npha)
Data URL:  https://archive.ics.uci.edu/static/public/936/data.csv


### Methods

Exploratory data analytics will be performed to better understand the data.  Classification algorithms will be used to predict the possiblity of healthy aging with healthy aging being determined by number of doctors visited. Logistic Regression, Decision Tree and Random Forest will be used to build predication models.  The prediction models will be compared using Precision, Recall and Accuracy.  Cross-Validation will be used to test the models stability and timing of the algorithms will be used to assess efficiency.  

##### Literature Review

Review of academic works that explore the topic of healthy aging and the features that are included in the dataset and the algorithms used by the researchers to analyze their data. 

###### Initial Results & Code

Initial Results indicated that neither of the three models were a good fit for prediction with the best fit having an accuracy score of 52%.  Chi-Square was used to select variables to test the models again.
The models using the filtered variables had similar accuracy scores (50%, 49%, 51%).

#######Limitations

There were three limitations identified:  Sample Size, Use of a pre-processed Dataset, and Methodology. 

########Conclusions

While prediction models were able to be created they were not very accurate in predicting the number of doctors an individual vistis.  Future research may want to use a larger sample size to build their predicition models and may want to use other machine learning algorithms. 
