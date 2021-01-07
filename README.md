# BERT_Model_AmazonRatingPrediction
This is a Kaggle Competition as part of the final project in University of Toronto CSC2515 Machine Learning course. The iPython notebook has the full implementation of fine tuning a BERT model and the result prediction ranked #6/135 in the Kaggle Competition.Competition link on Kaggle: https://www.kaggle.com/c/csc2515-rating-prediction/leaderboard 


The machine learning task is to predict the rating scores of reviews on Amazon, given the dataset that contains features such as review text, reviewer ID, Item ID. A pre-trained Bidirectional Encoder Representations from Transformers (BERT) model (bert-large-cased) is used to pre-process, tokenize, and train the review text. To predict rating of the Amazon reviews, a customized regression output layer is added on top of the BERT model for final output. The final performance has achieved a MSE of 0.31, surpassing the strong baseline of MSE 0.65, and ranked no.6 in the leaderboard. 

The final report for this project is also avilable.


