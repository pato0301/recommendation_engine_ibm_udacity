# Recommendation Engine

This project was designed to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles.

The Recommendation Engine will recommend articles to users base on knowledge and similar test. 
For new user will recommend top articles until it can make a knowledge of the interest of the new user.

# Project Motivation
Recommendation engines are one of the most important data science applications in use today. 
Data science is being used to recommend everything from music & movies to friends and new destinations. 

The three main branches of recommenders are:
- Knowledge-Based
- Collaborative Filtering 
- Content-Based

# Installations

This project requires Python 3.x and the following Python libraries installed:

- Nltk
- Pandas
- Progressbar
- Seaborn
- Scikit-learn
- pickle
- Matplotlib

# Summary:

The project contains the following tasks:

- Exploratory Data Analysis: This part is for data exploration.
- Rank Based Recommendations: To get started in building recommendations, I first find the most popular articles based on the most interactions. These are then the articles we might recommend to new users (or anyone depending on what we know about them).
- User-User Based Collaborative Filtering: In order to build better recommendations for the users of IBM's platform, I look at users that are similar in terms of the items they have interacted with. These items could then be recommended to similar users.
- Content Based Recommendations: Using NLP skills, I developed a content-based recommendation system.

# Data

- user-item-interactions.csv: file contains user interaction (which user read which article).
- articles_community.csv: file contains articles description (like description, title and body content).

# Acknowledgments

I would like to thank Udacity for this amazing project, and IBM for providing the data.
