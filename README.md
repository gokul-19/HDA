Mental Health Discourse on Reddit — Suicide & Depression Detection
Overview
This repository contains a data science pipeline for analyzing Reddit posts from the Suicide Watch subreddit. The goal is to explore patterns in mental health discourse, detect negative emotions, visualize keyword frequency, and apply topic modeling to uncover main discussion themes.

Dataset
Source: Kaggle Suicide Watch Dataset

Contents: Reddit posts focusing on suicide, depression, anxiety, and related emotional disclosure.

Project Workflow
Environment Setup

Uses Python 3, Jupyter Notebook, and libraries: pandas, numpy, seaborn, matplotlib, gensim, nltk, vaderSentiment, wordcloud, opendatasets.

Data Loading

Downloads Kaggle dataset and loads into a DataFrame.

Text Preprocessing

Cleans and tokenizes post text using NLTK (removes stopwords and non-alphabetic tokens).

Sentiment Analysis

Applies VADER for sentiment scoring.

Labels posts as positive, negative, or neutral.

Word Cloud Visualization

Generates a word cloud of the most common terms in user posts.

Keyword Frequency

Counts posts containing mental/emotional health keywords ("depression", "anxiety", "help", etc.)

Topic Modeling

Uses Gensim LDA on negative posts to extract top discussion topics.

Topic Assignment

Assigns dominant topic label to each negative post.

Visualizations

Displays sentiment distribution bar chart.

Plots boxplot of VADER scores per detected topic.

Export Results

Saves processed data to CSV for further analysis/sharing.

How to Run
Clone the repo and install requirements:

bash
pip install -r requirements.txt
or manually install:

bash
pip install pandas numpy scikit-learn matplotlib seaborn gensim nltk vaderSentiment wordcloud opendatasets
Setup Kaggle API credentials for dataset download (see Kaggle documentation).

Open HDA.ipynb in Jupyter Notebook and run all cells step by step.

Output Files
MentalHealthAnalysisResults.csv: Sentiment and topic assignments for all posts.

Images and plots: Sentiment distribution, word cloud, topic analysis.

Results
Clear patterns of emotional disclosure in at-risk posts.

Topical clusters of negative emotion and help-seeking detected via LDA.

Visual insights into the breadth and depth of language used on Suicide Watch.

Author
Name: [Your Name Here]

Contact: [your.email@domain.com]

Institution: [Your College/University or Organization]

License
This project is for academic and research purposes. See dataset’s Kaggle page for data usage rules.
