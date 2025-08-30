Hackathon Project: Location-Based Review Quality Assessment
📖 Project Description

Our project tackles the challenge of assessing the quality and relevance of location-based reviews. In today’s digital economy, platforms like Google Maps host millions of reviews that influence consumer decisions and business reputations. However, many reviews may be irrelevant, low-quality, or even misleading.

We built a solution that:

Scrapes reviews using the Google Maps API

Cleans and processes the text data

Analyzes sentiment and content quality using NLP techniques

Classifies reviews as relevant or non-relevant to help users and businesses quickly identify meaningful insights

Visualizes review distributions, keyword clouds, and sentiment trends

By filtering out noisy data and highlighting high-quality reviews, our tool helps both businesses and customers make better-informed decisions.

🎯 Problem Statement

From the challenge prompt:
“How can we assess the quality and relevancy of location-based reviews to improve trustworthiness and decision-making for users?”

Our solution addresses this by developing a machine learning–powered pipeline to:

Detect spammy or irrelevant reviews

Highlight authentic, detailed reviews

Provide transparent sentiment and relevance scores for each review

🛠️ Development Tools

Jupyter Notebook (Tiktok_Tech_Jam.ipynb)

Google Colab (for experimentation and training)

VSCode (for code refinement and debugging)

🔗 APIs Used

Google Maps API → for scraping location-based reviews

(Optional if applied in final version) OpenAI GPT models → for review relevance classification & semantic analysis

📚 Libraries & Frameworks

Data Handling: pandas, csv, pathlib

Natural Language Processing (NLP): nltk, vaderSentiment, scikit-learn (feature engineering, classification)

Machine Learning: RandomForestClassifier, GridSearchCV, StratifiedKFold

Visualization: plotly, wordcloud, matplotlib

Utilities: ipywidgets (interactive UI), collections.Counter

📂 Assets & Datasets

Google Maps Reviews Dataset (scraped using Google Maps API)

Custom Manually Labeled Dataset (used for supervised training and evaluation of review relevance)

🚀 Key Features

✅ Automatic scraping of Google Maps reviews

✅ Sentiment analysis (positive, neutral, negative)

✅ Review quality/relevance classification

✅ Visual insights (word clouds, review trends, sentiment charts)

✅ Interactive widgets for exploration
