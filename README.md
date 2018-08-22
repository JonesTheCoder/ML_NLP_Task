Util_NLP_README

Tutorials:
https://towardsdatascience.com/multi-class-text-classification-with-scikit-learn-12f1e60e0a9f
https://www.kaggle.com/itratrahman/nlp-tutorial-using-python/notebook
https://www.toptal.com/machine-learning/nlp-tutorial-text-classification

Notes:

Total time spent: ~ 9 hours

While I have programmed a few NLP algorithms in Processing.js using the RiTa.js Library, this was my first time utilizing the NLTK and Scikit-Learn NLP libraries in Python.

The three tutorials listed at the top seemed to be the most applicable, so after working through them and understanding conceptually how they worked, I transposed them to address the challenge regarding a company’s business description and the predicted sector name.

In this program I wrote very little original code. It was mainly just correctly combining and substituting variables related to the company dataset and fixing syntax issues like converting floats to strings and things like that. This line in section [9] is a specific example:
        df.Business_Description = df['Business_Description'].values.astype('U').tolist()"

Moving forward, I think completing more NLP challenges would help me increase speed of finding solution and the efficiency of the solution. Also, I plan on analyzing other possible models such as Logistic Regression, Linear Support Vector Machine, and Random Forest. 
