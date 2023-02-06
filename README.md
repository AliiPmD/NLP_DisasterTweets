# Natural Language Processing with Disaster Tweets
## Predict which Tweets are about real disasters and which ones are not
-------
### Abstract: 
>##### Twitter has become an important communication channel in times of emergency. The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time.   Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).  But, it’s not always clear whether a person’s words are actually announcing a disaster.
>##### In this notebook, I've build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t.   
>   
>   ##### *Also I've created two notebook, one of them is commented and all fully detailed and easy to read and train, And other one is functional implementation of first one and more clean. 

------   
### Dataset:
> ##### The dataset that i've used in this notebook is available on Kaggle site. [[link]](https://www.kaggle.com/competitions/nlp-getting-started)

---   
### In this notebook I've performed some steps such as :
> #### 1)  EDA : a little look at dataset with some graphs
> #### 2) Clean data in two steps:
> > - ##### Remove duplicated tweets
> > - ##### Find similar tweets and drop them
>
> #### 3) Extract some features such as:
> > - ##### Lenght of tweets
> > - ##### Count of words in tweets
> > - ##### Count of numbers in tweets
> > - ##### Count of sentenses in tweets
> > - ##### Count of hashtags in tweets
> > - ##### Text of hashtags
> > - ##### Count of mentions in tweets
> > - ##### Text of Mentions
> > - ##### Count of links in tweets
> > - ##### Word per lenght of tweet
> > - ##### Punctuation count per tweet lenght
> > - ##### Uppercase letters count per tweet lenght
> > - ##### MinMaxScaling for numeric columns
> 
> #### 4) Process Tweets such as:
> > - ##### Lowercase tweets
> > - ##### Remove URLs
> > - ##### Remove Punctuation
> > - ##### Remove Short words <=2 chars
> > - ##### Remove Stopwords
> > - ##### Lemmatization
> > - ##### GetDummy for keyword column
>
> #### 5) TF-IDF:
> > - ##### TF-IDF on tweets
> > - ##### TF-IDF on text of hashtags
> > - ##### TF-IDF on text of mentions
>
> #### 6) Train and test models:
> > - ##### GradientBoostingClassifier
> > - ##### NaiveBayes
> > - ##### LogisticRegression
> > - ##### SVM

#### And I've got approx. 0.8 score on main test set on kaggle site.

---