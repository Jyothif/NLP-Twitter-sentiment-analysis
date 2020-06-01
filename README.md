# Twitter Sentiment Analysis project overview

* Sentiment analysis where task will be to classify a set of tweets into two categories: 1. racist, 2.non-racist
* Sentiment analysis(also known as opinion mining)is one of the many applications of Natural Language Processing.
* It is a set of methods and techniques used for extracting subjective infromation from text or speech,such as attitudes.
* In simple terms,it involves classifying a text as positive, negative or neutral.

# code and Resources
* **Python:** 3.7
* **Packages:** `Numpy`,`Pandas`,`Matplotlib`,`Seaborn`,`Matplotlib`,`re`,`NLTK`,`gensim`,`sklearn`,`WordCloud`,`Word2Vec`

* **Installation:** by conda run  prompt

    * **Gensim:** **`conda install -c anaconda gensim`**
    * **Word2vec:** **`conda install -c anaconda word2vec`**   
    * **Wordcloud:** **`conda install -c conda-forge wordcloud`**
    
    
 
         

     

* **Jupyter Notebook:** 6.0.3
* **Dataset Resource:** https://datahack.analyticsvidhya.com/contest/practice-problem-twitter-sentiment-analysis/

# Data Cleaning

* In this step i went through data inspection,Clenaing of the data and standardization of text.

* Data consists of `id` `label`=(0 or 1) and `tweet`.
* Tweets consists of @user, # tags and repeated words, beautified words and hatreds..So this is our task is to remove all those #tags, user, and special characters everything. at last we will b remianing with tweets which demonstrates the purpose of this model.

* I have Regular rexpression for Removing special characters('#')
* Removing Short words('hmm', 'ha','oh' etc)
* I also performed text normalization using  PorterStemmer function to normalize the tweets


# Exploratory Data Analysis(EDA)

![](https://github.com/Jyothif/NLP-Twitter-sentiment-analysis/blob/master/images/download%20(2).png)
![](https://github.com/Jyothif/NLP-Twitter-sentiment-analysis/blob/master/images/download%20(1).png)![](https://github.com/Jyothif/NLP-Twitter-sentiment-analysis/blob/master/images/tweets.png)

* Bag of Word Features
* TF-IDF Features 
* Word2Vec Features and Doc2Vec Embedding are also performed


# Model Building
 
 * I have used four algorithms to build model and check which alogirthm is performing the best.
 
      * Logistic Regression
      * SVM
      * Random Forest
      * XGBoost
      
 * I also used evaluation metric i.e., F1 Score : the important Components of F1 Score are:
        
      * True Positive(TP)
      * True Negative(TN)
      * False Positive(FP)
      * False Negative(FN)
      
  
      
# Model Performance

* By using Evaluation Metric F1 Score uisng 

**Logistic Regression model**
  
   * BOW( Bag of word) : 53.04
   * Tf-idf feature score : 54.46
   * Word2Vec Faeture Score :
   * Doc2Vec Feature Score : 40.06
   
   
   **Support Vector Machine(SVM**
  
   * BOW( Bag of word) : 50.88
   * Tf-idf feature score : 51.04
   * Word2Vec Faeture Score :
   * Doc2Vec Feature Score : 24.38
   
   
   
   
   
   

   
 





