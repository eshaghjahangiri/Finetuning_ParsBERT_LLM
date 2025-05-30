# Fine-tuning ParsBERT LLM for text classification

In this repository, I fine-tuned the ParsBERT LLM which is the BERT Architecture LLM for Persian language.

I fine-tuned the ParsBERT to classify the sentiment of social media messages about stock market. For the sentiment, I mean to classify which messages are expected the market to go up, positive (bullish), and which of them are expecting the market to go down, negative (bearish).
I scraped the message from the website [Sahamyab.com](https://www.sahamyab.com/stocktwits) which is the Stocktwits.com version for the stock markets in Iran.

# Model Performance
Overall F1 Score
The overall F1 score of the model is 0.7747.

## Detailed Classification Report

| Class     | Precision | Recall | F1-Score | Support |
|-----------|-----------|--------|----------|---------|
| Negative  | 0.77      | 0.77   | 0.77     | 896     |
| Positive  | 0.78      | 0.78   | 0.78     | 915     |

## Accuracy
The model achieves an accuracy of 77% on the test dataset, with a total of 1811 samples.



