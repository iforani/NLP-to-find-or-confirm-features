# **Using NLP with Yelp to Find Business Features**
---
---
---

### Problem Statement

<br>

I want to know if one can use Natural Language Processing and data from Yelp to locate businesses/enterprises with a specific feature

<br>

---

### Executive Summary

<br>

For this investigation I will be attempting to find businesses having a specific desirable (or undesirable) feature by using NLP. I will be using a 
dataset that consists exclusively of businesses found on Yelp and a collection of user provided reviews for those businesses, along with the 
NLP power of spaCy.  Each row of data will contain a business and a feature column made up of a miniature corpus of the reviews.  The reviews column 
of the miniature corpi will be tokenized by spaCy and then analyzed for words related to the feature we are in search.  The appearance 
of feature related words will be counted and then used to calculate a score by which a business will be classified as having the feature in question or not.

<br>

---

### Data

<br>

|Brooklyn|   |   |   |
|---|---|---|---|
|Zip Codes|[./data/brooklyn/bk_zips.csv](./data/brooklyn/bk_zips.csv)|   |   |
|   |   |   |   |
|Businesses|[./data/brooklyn/final_bklyn_biz.csv](./data/brooklyn/final_bklyn_biz.csv)|   |   |
|   |   |   |   |
|Reviews|[./data/brooklyn/reviews/bk_biz_and_rev.csv](./data/brooklyn/bk_biz_and_rev.csv)|   |   |

<br>

---
### Code

<br>

|Brooklyn|   |   |   |
|---|---|---|---|
|Zip Codes|[./code/zip_codes.ipynb](./code/zip_codes.ipynb)|   |   |
|   |   |   |   |
|Businesses|[./code/bkln_biz_combine.ipynb](./code/bkln_biz_combine.ipynb)|   |   |
|   |   |   |   |
|Reviews|[./code/bkln_reviews.ipynb](./code/bkln_reviews.ipynb)|   |   |
|   |   |   |   |
|Analyzer|[./code/bk_biz_analyzer.ipynb](./code/bk_biz_analyzer.ipynb)|   |   |

<br>

---
### The Deck

<br>

| |
|---|
|**[Project Presentation Deck](https://github.com/iforani/NLP-to-find-or-confirm-features/blob/main/Hitting%20the%20Bullseye%20with%20NLP.pdf)**|



<br>

---
### Conclusion

<br>

The model is picking up on the targeted word and scoring the businesses as it pertains to the feature in question.  At first glance there is a high level of confidence in accuracy, but more surpervised learnining needs to be conducted to accurately label the businesses run through the model.  Once the set is confirmed it will be used to predict the classification of other businesses not in the training set.  This will be done with a combination of NLP matching and word vectorization.  After this model proves out on the selected words locally it will be moved to the cloud to harness the power of cluster computing and parallelization.  As the model and compute evolve the model will be adapted to take a user provided feature and return on the spot results.

<br>

---


