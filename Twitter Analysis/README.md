# Project Overview
- Created a Deep Learning model that classifies a tweet into Dister or not Dister based on the textual data using Natural Language Processing.

# Resources Used
- Packages: pandas, numpy, sklearn, Tensorflow, keras, matplotlib, seaborn, nltk.
- Dataset on Kaggle: https://www.kaggle.com/c/nlp-getting-started/data

# Exploratory Data Analysis (EDA)
- Plotted countplot for Dister vs. Not Dister
- 
![count](Pictures/count.png)

- Plotted Number of Characters in tweets.

![count](Pictures/no_char.png)

- Plotted CountPlot of top most Common Words in dataset text.

![](Images/spam.png) ![](Images/ham.png) 

# Data Cleaning
- Removing special character and numbers using regular expression
- Converting the entire sms into lower case
- Tokenizing the sms by words
- Removing the stop words
- Lemmatizing the words
- Joining the lemmatized words
- Building a corpus of messages

# Model Building and Evaluation
- Building using Multinomial Naive Bayes : 0.97
- Building using Decision Tree:  0.95
- Building using Random Forest: 0.97

# Used Model 
- Random Forest: 0.97

![](Images/rf.png)

# Model Prediction 

![](Images/prediction.png)
