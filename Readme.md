# Customer Review Analysis (Text Mining, Sentiment Analysis & Topic Modelling)  
  
## Overview  
This project analyses women’s clothing e-commerce customer reviews using text mining, sentiment analysis, topic modelling, and additional statistical techniques to extract meaningful insights and customer behaviour patterns.  
  
---  
  
## Dataset  
The dataset consists of anonymised customer reviews from an e-commerce platform. Each row represents a single customer review with multiple associated features.  
  
**Note:** The dataset is not included in this repository as it is part of a coursework assignment and subject to academic submission restrictions.  
  
---  
  
## Task A – Text Mining  
Text preprocessing and cleaning techniques were applied to prepare the data for analysis.  
  
### Methods Used:  
- Text cleaning (removal of punctuation, numbers, and stopwords)  
- Tokenisation and normalisation  
- Stemming/Lemmatisation  
- Document-Term Matrix (DTM / TDM)  
  
### Visualisations:  
- Word clouds  
- Term frequency plots  
- Most frequent words analysis  
  
---  
  
## Task B – Sentiment Analysis  
Customer sentiment was analysed and classified using lexicon-based approaches.  
  
### Methods Used:  
- Bing, NRC, and AFINN sentiment lexicons  
- Polarity scoring (positive, negative, neutral)  
- Aggregation of sentiment across reviews  
  
### Visualisations:  
- Sentiment distribution plots  
- Emotion classification (NRC)  
- Sentiment comparison with ratings  
- Word contribution to sentiment  
  
---  
  
## Task C – Topic Modelling  
Topic modelling was applied to identify hidden themes in customer reviews.  
  
### Methods Used:  
- LDA (Latent Dirichlet Allocation)  
- NMF (Non-negative Matrix Factorisation)  
- STM (Structural Topic Modelling)  
  
  
### Visualisations:  
- Topic-term distributions  
- Top words per topic  
- Topic clustering plots  
- Topic proportion across documents  
  
---  
  
## Task D – Further Exploration  
Additional analytical techniques were used to extract deeper insights from the dataset.  
  
### Methods Used:  
- POS (Part-of-Speech) tagging  
- Regression analysis on sentiment and textual features  
- Feature-based analysis of review structure  
  
---  
  
## Tools & Technologies  
- R  
- tidyverse (dplyr, ggplot2)  
- tidytext  
- tm, topicmodels, stm  
- Sentiment lexicons (Bing, NRC, AFINN)  
  
---  
  
## Conclusion  
  
This study integrates multiple text mining and analytical techniques to develop a holistic understanding of customer experiences in retail reviews.  
  
LDA topic modelling reveals broad, coherent themes and shows that experiential topics such as style, wearability, and retail experience are consistently associated with high ratings and positive sentiment. NMF further refines these insights by producing more interpretable, parts-based topics that emphasise distinctive issues related to fit, fabric quality, and post-purchase experience.  
  
STM extends this analysis by linking topics to customer behaviour, demonstrating that comfort and accurate fit significantly increase the likelihood of recommendation, while delivery and return issues drive dissatisfaction. Regression analysis confirms the predictive importance of these themes, and POS-based phrase extraction provides fine-grained interpretability by revealing how customers explicitly express praise and complaints in their own words.  
  
Taken together, the findings consistently highlight fit accuracy, comfort, and perceived quality as the strongest drivers of customer satisfaction, while shortcomings in online representation and returns emerge as the primary sources of dissatisfaction, offering clear and actionable insights for product and service improvement.  
