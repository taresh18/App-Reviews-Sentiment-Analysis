# App-Reviews-Sentiment-Analysis
### Dataset :
Used Google play scraper to build dataset containing the ratings and user reviews of top 15 apps in Google Play Store. </br>
Reviews with a rating of 1 or 2 are labelled as negative sentiment, rating 3 as neutral sentiment and rating 4 and 5 as positive sentiment. </br>

### Training :
Used tokenizer from the transformers library for encoding </br>
Used AdamW (adam with weight decay) optimiser and cross entropy loss. </br>
Trained for 10 epochs </br>


