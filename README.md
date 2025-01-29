Kaggle Reddit Mental Health Data: 
https://www.kaggle.com/datasets/neelghoshal/reddit-mental-health-data

Problem Statement: 
This project aims to utilize Reddit posts from mental health-related subreddits to develop a classifier that accurately classifies posts into five categories defined in the dataset: 0 = Stress, 1 = Depression, 2 = Bipolar Disorder, 3 = Personality Disorder, and 4 = Anxiety. By analyzing linguistic patterns, word usage, and phrases commonly associated with these mental health conditions, the model seeks to identify and differentiate the unique characteristics of each category.
This project will provide insights into the relationship between language and mental health, ultimately contributing to the development of tools for identifying at-risk individuals and enabling timely interventions. For example, mental health apps and forums can use this model to flag posts indicative of potential serious mental health conditions and ensure their uses receive timely assistance. Social media platforms like Reddit and Twitter can use the tool to enhance their content moderation and direct users to appropriate resources, such as meditation apps or mental health/suicide hotlines. In addition, governments and healthcare providers can use the insights from this project to design targeted support campaigns addressing the most common mental health struggles discussed online. 

Text Analytics Approach Overview:
- Tokenizing and POS-tagging to prepare for sentiment analysis
- Removing stop words and normalizing text using text processing techniques such as normalizing, stemming/lemmatization (not applying to VADER).
- Using Bag of Words (BoW) to capture word frequencies and identify simple patterns in the data.
- Applying TF-IDF to emphasize important words and reduce the impact of common terms, improving feature quality.
- Applying VADER to create the sentiment score.
- Implementing word association techniques such as the Lift and MDS plotting to use these associations and patterns to determine the level of impact that is having on the audiences.
- Assigning a sentiment score to new Reddit posts based on the text features.
- Classifying new Reddit posts into the target categories (0 = Stress, 1 = Depression, 2 = Bipolar Disorder, 3 = Personality Disorder, and 4 = Anxiety) using 2 classification algorithms from the following: Logistic Regression, Random Forest, Neural Network, Naive Bayes, and KNN. 
