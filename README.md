# NLP-PROJECT<br>
                                        Brand Sentiment Analysis using Twitter Mentions

PART - I  EXTRACTION OF TWITTER DATA<br>

1. Run the GetTweetFinal.py script <br>
This script has the GetOldTweets3 module which fetches tweets based on the input parameters<br><br>
2. The tweets have been downloaded based on certain parameters like the brand name, the start and end date between which the tweets
   were done, and the geometric location from where the tweet was done.<br><br>
3. All the tweets are saved in a CSV file in the working directory<br>

-----------------------------------------------------------------

PART - II  TWEET SENTIMENT ANALYSIS

1. Import the training dataset from NLTK <br>
For training the NLTK model, we have used an already existing dataset : movie reviews. 
We have used NLTK to download the movie_reviews dataset. <br><br>
2. Preprocess data and set parameters for training the model<br>
Divide the dataset into training and testing dataset(80% dataset is kept for training and 20% is kept for testing). <br><br>
3. Train and test model on training set<br>
Train the model using training dataset and testing the model using the testing dataset. We are using Naive Bayes Classifier to classify
the tweets into positive or negative emotion based on the positive or negative words obtained from the training dataset. <br><br>
4. Run the saved model on the validation data which we got from Twitter <br>
The model that is trained, is used to find the sentiment of the tweets that were collected in the previous module.<br><br>


------------------------------------------------------------------

END OF README
