This a bert-base-multilingual-uncased model finetuned for sentiment analysis on product reviews in six languages: English, Dutch, German, French, Spanish and Italian. It predicts the sentiment of the review as a number of stars (between 1 and 5).

This model is intended for direct use as a sentiment analysis model for product reviews in any of the six languages above, or for further finetuning on related sentiment analysis tasks.

website: https://huggingface.co/nlptown/bert-base-multilingual-uncased-sentiment# 

In this project I've runned Hugging Face Transformers and BERT to be able to calculate sentiment using a single prompt but also leverage BeaultifulSoup to scrape reviews from Yelp to be able to calculate sentiment on a large scale. 