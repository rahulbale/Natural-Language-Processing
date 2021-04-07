# Project Overview
• Created a machine learning model that classifies a SMS into SPAM or HAM (normal) based on the textual data using Natural Language Processing.

# How will this project help?
• This project helps in filtering/cleaning the SMS from the phone.

# Resources Used
• Packages: pandas, numpy, sklearn, matplotlib, seaborn, nltk.
• Dataset by UCI Machine Learing on Kaggle: https://www.kaggle.com/uciml/sms-spam-collection-dataset

# Exploratory Data Analysis (EDA)
• Plotted countplot for SMS labels Spam vs. Ham
• Plotted CountPlot of top most Common Words in dataset text.
![](Photos/AdminPage.png)
![](Photos/AdminPage.png)

# Data Cleaning
• Removing special character and numbers using regular expression
• Converting the entire sms into lower case
• Tokenizing the sms by words
• Removing the stop words
• Lemmatizing the words
• Joining the lemmatized words
• Building a corpus of messages

# Model Building and Evaluation
• Building using Multinomial Naive Bayes : 0.97
• Building using Decision Tree:  0.95
• Building using Random Forest: 0.97

# Used Model 
• Random Forest: 0.97
