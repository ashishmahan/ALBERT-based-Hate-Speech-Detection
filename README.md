# ALBERT-based-Hate-Speech-Detection

This project focuses on developing a hate speech detection model using the ALBERT architecture from the Transformers library. The model was trained on the Twitter Hate Speech and Offensive Language Dataset (HSOL), which includes around 30,000 tweets. Each tweet is classified into two categories: hate speech (label 1) and non-hate speech (label 2).

# Methods:

Data Preparation: The dataset was filtered to include only relevant columns (tweet and class). The class column was mapped to binary labels: 1 for hate speech and 0 for non-hate speech.
Tokenization: Tweets were tokenized using the pretrained ALBERT tokenizer, handling padding and truncation to ensure uniform input length.
Model Training: ALBERT for Sequence Classification was used to build the model. The training process involved setting up training arguments and using the Trainer API from the Transformers library.
Evaluation: The model's performance was assessed on a validation set, with key metrics including precision, recall, and accuracy.

# Results:

Precision: 96.15%

Recall: 96.15%

Accuracy: 93.75%
