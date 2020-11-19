# Using NLP with Yelp to Find Business Features
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
made up of the miniature corpi for each business will be tokenized by spaCy and then analyzed for words related to the feature we are in search.  The appearance 
of feature related words will be counted and then used to calculate a score by which a business will be classified as having the feature in question or not.

<br>

---

### Data

<br>

Data

<br>

---

### Conclusion

<br>

The model is picking up on the targeted word and scoring the businesses as it pertains to the feature in question.  At first glance there is a high level of confidence in accuracy, but more surpervised learnining needs to be conducted to accurately label the businesses run through the model.  Once the set is confirmed it will be used to predict the classification of other businesses not in the training set.  This will be done with a combination of NLP matching and word vectorization.  After this model proves out on the selected words locally it will be moved to the cloud to harness the power of cluster computing and parallelization.  As the model and compute evolve the model will be adapted to take a user provided feature and return on the spot results.

<br>

---


