# 20newsgroups-text-classification

## Summary

Text classification (NLP) applied to 20 Newsgroups dataset

## Dataset

20newsgroups is a collection of about 20000 newsgroups documents. It is directly available in scikit-learn : from sklearn.datasets import fetch_20newsgroups

There are 20 newsgroups:
* comp.graphics
* comp.os.ms-windows.misc
* comp.sys.ibm.pc.hardware
* comp.sys.mac.hardware
* comp.windows.x rec.autos
* rec.motorcycles
* rec.sport.baseball
* rec.sport.hockey sci.crypt
* sci.electronics
*  sci.med
*  sci.space
*  misc.forsale talk.politics.misc
*  talk.politics.guns
*  talk.politics.mideast talk.religion.misc
*  alt.atheism
*  soc.religion.christian


See the following websites for more information about 20newsgroups.
* http://qwone.com/~jason/20Newsgroups/
* https://www.kaggle.com/crawford/20-newsgroups
* https://scikit-learn.org/0.19/datasets/twenty_newsgroups.html

Notebook
* Natural Language Processing (NLP)
  * Standard Count Vectorizer
  * TFIDF transformer 
* Machine learning models
  * Multi naive Bayes Classifier
  * Linear Support Vector Machine classifier
* Evaluation of the accuracy score
