# **Information**
|StuID  |        Name       |     Kaggle    |       Github      |
|-------|-------------------|---------------|-------------------|
|1752052|Dang Huu Phuoc Vinh|[V_Notebook](https://www.kaggle.com/danghuuphuocvinh)|[V_Github](https://github.com/DangHuuPhuocVinh/data_science_application)
|1753097|Le Nguyen Minh Tam |[T_Notebook](https://www.kaggle.com/minhtamlenguyen)|[T_Github](https://github.com/lnmtam1999)
# **Project in colab (for presenting)**
[Model RoBerta _ Colab](https://colab.research.google.com/github/DangHuuPhuocVinh/data_science_application/blob/main/tweet_sentiment_extraction_2.ipynb)
# **Project in kaggle (for running)**
[Tweet Sentiment Extraction](https://www.kaggle.com/code/danghuuphuocvinh/report/edit/run/102204871)
# **Work plan**
 [Work plan of group](https://docs.google.com/spreadsheets/d/10moa8xnprmD-MkfVzvn73UQyaCyHGVSmkDy8GRSXU4Y/edit#gid=0)
# **Competition**
 [Tweet Sentiment Extraction](https://www.kaggle.com/competitions/tweet-sentiment-extraction) organized by [Kaggle](https://www.kaggle.com/)
## **Prize**
 **15000 USD**
## **Link solution** 
 https://www.kaggle.com/code/minhtamlenguyen/tensorflow-roberta-0-705
 <br>
 https://www.kaggle.com/code/jerifate/tweet-sentiment-blue-visualization-with-bert
 <br>
 [Google Colab](https://colab.research.google.com/github/lnmtam1999/BigData/blob/main/Amazon_Craw_Bertl.ipynb)
## Description
  E.g: "My ridiculous dog is amazing." [sentiment: positive]

  With all of the tweets circulating every second it is hard to tell whether the sentiment behind a specific tweet will impact a company, or a person's, brand for being viral (positive), or devastate profit because it strikes a negative tone. Capturing sentiment in language is important in these times where decisions and reactions are created and updated in seconds. But, which words actually lead to the sentiment description? In this competition you will need to pick out the part of the tweet (word or phrase) that reflects the sentiment.

  In this competition we've extracted support phrases from [Figure Eight's Data for Everyone platform](https://appen.com/datasets-resource-center/). The dataset is titled Sentiment Analysis: Emotion in Text tweets with existing sentiment labels, used here under creative commons attribution 4.0. international licence. Your objective in this competition is to construct a model that can do the same - look at the labeled sentiment for a given tweet and figure out what word or phrase best supports it.
  
  - Input: textID, text and sentiment
  - Output: selected_text
 
## **Columns**
 -  textID - unique ID for each piece of text
 -  text - the text of the tweet
 -  sentiment - the general sentiment of the tweet
 -  selected_text - [train only] the text that supports the tweet's sentiment
## **Meaningful**
 - After doing this project, we can have a dataset with the phrases that were selected for using at any other NLP project
 - Can use for detecting some keywords that have sentiment 

## **Evaluation**
 ![img](https://user-images.githubusercontent.com/35680794/174698744-57b2f116-fbe4-4fb6-9216-2e83e0494dca.png)
