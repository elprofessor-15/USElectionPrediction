# USElectionPrediction
This project performs sentiment analysis on two datasets containing user text. The text is preprocessed by removing stopwords, punctuation, URLs, HTML tags, and lowercasing. Using the VADER lexicon, sentiments (Positive, Negative, Neutral) are determined, providing insights into text sentiment distribution.

# Sentiment Analysis Project

## Project Description
This project performs sentiment analysis on two datasets containing user-generated text. The text is preprocessed using the following steps:
- Lowercasing all text
- Removing stopwords, punctuation, URLs, and HTML tags

Once cleaned, the VADER (Valence Aware Dictionary and sEntiment Reasoner) lexicon is used to analyze the sentiment of each text entry. Sentiments are classified into:
- **Positive**
- **Negative**
- **Neutral**

The project outputs:
- Cleaned text
- Sentiment labels
- Distribution of sentiment categories for further analysis

## Tools and Libraries
- **Python**
- **NLTK** (Natural Language Toolkit)
- **Pandas**

## Steps Performed
1. Data cleaning and preprocessing
2. Sentiment classification using VADER
3. Sentiment analysis summary: counts and distribution

## Use Case
This analysis is ideal for evaluating user sentiment from social media posts, reviews, or any other text-based data to gain insights into the emotional tone.

---
**Example Output:**
| Text                        | Cleaned Text        | Sentiment |
|-----------------------------|---------------------|-----------|
| "@JoeBiden So did Lying Barr" | so did lying barr   | Negative  |
| "@JoeBiden I will vote..."    | i will vote         | Neutral   |

