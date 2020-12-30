---
name: Yelp Me Rate This (Yelp Rating Prediction)
img: ../imgs/yelp.jpg
img_size: 250px
links:
 - name: Code
   value: https://github.com/aatifjiwani/yelp-rating-predictor/
 - name: Report
   value: ../pdfs/yelp.pdf
   last: true
ordering: 2
---
Experimented with various custom and state-of-the-art NLP models to predict the star rating of any given Yelp review for any business. Used PyTorch to build a Bi-LSTM with a decoder and a base transformer, and used HuggingFace to load pre-trained large transformers such as RoBERTa and XLNet. After training and evaluation on the Yelp dataset, our team achieved a peak performance 
or near 80% accuracy on the full dataset and 60% on the challenge datasets. 