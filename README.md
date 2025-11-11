# 🧠 Mental Health Discourse on Reddit — Suicide & Depression Detection
### 🔍 Overview
This project explores **mental health discourse** on Reddit’s *r/SuicideWatch* community using **Natural Language Processing (NLP)**. It focuses on identifying **sentiment trends**, **keyword patterns**, and **discussion topics** related to suicide, depression, and emotional support. The goal is to understand how individuals express mental distress and seek help through online communities.
### 📊 Dataset
- **Source:** [Kaggle — Suicide Watch Reddit Dataset](https://www.kaggle.com)  
- **Platform:** Reddit (*r/SuicideWatch*)  
- **Contents:** Reddit posts discussing suicidal ideation, depression, anxiety, and self-help.  
- **Attributes:** Post ID, text, timestamp, upvotes, and comment count.
### ⚙️ Workflow
1. **Environment Setup** – Install dependencies and prepare the NLP environment.  
2. **Data Loading** – Load Reddit post data and inspect structure and quality.  
3. **Text Cleaning** – Normalize and preprocess text by removing punctuation, URLs, symbols, and stopwords.  
4. **Sentiment Analysis** – Perform VADER sentiment analysis to classify posts into positive, neutral, or negative.  
5. **Word Cloud** – Visualize the most common words to highlight recurring emotional themes.  
6. **Keyword Frequency** – Track emotion-related terms like *sad*, *help*, *alone*, *life*, *die*, and *love*.  
7. **Topic Modeling** – Apply Latent Dirichlet Allocation (LDA) to negative posts to extract main discussion topics.  
8. **Topic Assignment** – Label posts with dominant topics such as hopelessness, coping, or support.  
9. **Visualization** – Generate sentiment distributions, topic clusters, and word clouds.  
10. **Export Results** – Save processed data to `MentalHealthAnalysisResults.csv`.
### 📉 Results Summary
- Over **70% of posts** exhibit **negative sentiment**, consistent with distress-related content.  
- Frequent terms include *help*, *life*, *alone*, showing strong emotional disclosure.  
- LDA revealed themes of **hopelessness**, **emotional fatigue**, and **seeking help**.  
- Reddit serves as an important **peer-support platform** for open mental health discussion.
### 🚀 How To Run
1. Install dependencies:  
   `pip install pandas numpy matplotlib seaborn gensim nltk vaderSentiment wordcloud opendatasets`  
2. Configure your **Kaggle API credentials** to access the dataset.  
3. Open `HDA.ipynb` in **Jupyter Notebook**.  
4. Run all cells sequentially.  
5. View generated plots and exported CSV results.
### 📁 Project Files
| File | Description |
|------|--------------|
| `MentalHealthRedditAnalysis.ipynb` | Main notebook containing preprocessing, analysis, and visualization |
| `MentalHealthAnalysisResults.csv` | Processed dataset with sentiment and topic results |
| `README.md` | Project overview and documentation |
### 👨‍💻 Author
**Gorthi Gokul**  
Department of Data Science and Artificial Intelligence  
Indian Institute of Information Technology Dharwad  
📧 22bds026@iiitdwd.ac.in
### 🧩 Keywords
`Reddit` • `Mental Health` • `Depression` • `Suicide Watch` • `NLP` • `Sentiment Analysis` • `Topic Modeling` • `Data Science`

