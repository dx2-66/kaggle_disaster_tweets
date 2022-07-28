# Kaggle Disaster Tweets

https://www.kaggle.com/competitions/nlp-getting-started/

How to score your 50-ish place (20-ish excluding the exploits) while doing absolutely nothing.

Model: roberta-large, base one is fine, too.

NB:
 - #hashtags seem important, preserving them improves the accuracy a bit;
 - t.co URLs were dropped.
 - Locations and keywords ignored.

Makes use of those nice Huggingface units:
- transformers
- datasets
- accelerate

Other units engaged:
- pandas
- scikit-learn
- PyTorch
- numpy
- scipy
- Matplotlib
- Seaborn
