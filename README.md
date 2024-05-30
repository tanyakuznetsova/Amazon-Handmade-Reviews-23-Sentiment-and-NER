# Amazon-Handmade-Reviews-23-Sentiment-and-NER
## Overview
This project compares the performance of two NLP systems, AWS Comprehend and SpaCy, on a subset of the Amazon Handmade reviews dataset. The tasks include sentiment analysis and named entity recognition (NER).

## Data
The dataset used is a subset of the Amazon Reviews 2023 dataset collected by Professor Julian McAuley and his team at UCSD, containing 664,162 reviews of Amazon Handmade items.
Source: [Amazon Reviews 2023](https://amazon-reviews-2023.github.io/)
Subset: 664,162 reviews of Amazon Handmade items

## NLP Tools
**AWS Comprehend**: Amazon's proprietary NLP service
**SpaCy**: Open-source NLP library
eng_spacysentiment: SpaCy-based sentiment analysis extension 

## Key Findings
- **Sentiment Analysis**:
AWS Comprehend generally captures sentiment nuances better, especially in short reviews.
SpaCy tends to struggle and misclassify short (one-two words) reviews in particular. 

- **NER**: 
SpaCy provides more detailed entity categorization (e.g., distinguishing between CARDINAL, ORDINAL, MONEY), whereas AWS Comprehend uses broader generalizations (e.g., QUANTITY for any numeric expressions).


## Contact
For any questions, please contact me [Tanya Kuznetsova](mailto:tanya_kuznetsova@icloud.com).
