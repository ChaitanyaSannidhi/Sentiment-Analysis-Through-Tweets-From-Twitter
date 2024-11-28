Sentiment Analysis on Tweets
Overview
This project processes tweets to analyze their sentiment (positive, negative, or neutral) using various data cleaning and feature extraction techniques. The pipeline includes cleaning, preprocessing, feature engineering, and model training for sentiment classification.

Key Components
Data Cleaning (cleanup.py):
Removes URLs, usernames, special characters, and numbers from tweets to prepare them for analysis.

Data Preprocessing (preprocessing.py):
Tokenizes tweets, extracts features like hashtags, mentions, and emoticons, and builds word lists and n-grams for model training.

How to Run
Set up your environment:

Install required Python packages:
bash
Copy code
pip install -r requirements.txt
Data Cleanup:

Use the TwitterCleanuper class in cleanup.py to clean your raw tweet dataset.
Preprocessing & Feature Engineering:

Load and preprocess data using the TwitterData class in preprocessing.py.
Extract features like n-grams, hashtags, and sentiment indicators.
Project Structure
plaintext
Copy code
├── data                    # Contains raw and processed tweet data
├── src
│   ├── cleanup.py           # Tweet cleaning methods
│   └── preprocessing.py     # Preprocessing and feature extraction
├── .gitignore               # Ignored files
├── README.md                # Project documentation
└── requirements.txt         # List of dependencies
