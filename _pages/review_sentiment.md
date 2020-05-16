---
title: "Sentiment Classification of Game Reviews "
permalink: /review_sentiment/
---

<img src="/cv-portfolio/assets/images/steam600.png" />

### Sentiment Classification of Game Reviews with Semi-supervised Topic Analysis
<div style="color:#97AAC3">
  Group Project (3 persons) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Feb, 2020 - Apr, 2020
</div>
*******************
  
  
#### Introduction
Understanding sentiment of game reviews is important for game developers as well as investment companies. However, gaming is a domain in which in-group users have mutual but specific words and expressions which makes text mining harder. Our project focused on sentiment classification problems on game reviews from Steam. Beyond the generic word2vec embeddings, we applied the semi-supervised topic analysis method guided LDA, which can incorporate domain knowledge to generate probability distribution of a review belonging to different topics. We found that performance of Random Forest and Logistic Regression improved when using LDA features or LDA features and word2vec embeddings together, compared with using word2vec only. We also experimented with the popular Gradient Boosting Machine for sentiment classification and applied the Bayesian Optimization method to speed up hyperparameter tuning process. The F1 score of our final model is 0.8997. 

<img src="/cv-portfolio/assets/images/sentiment1.png" />

<br/>

#### Key Contributions and Highlights
1.Proposed the project idea that applying semi-supervised topic analysis to improve sentiment classification of game reviews, which is an effect way to incorporate domain knowledge into word embeddings.  

<img src="/cv-portfolio/assets/images/sentiment2.png" />

<img src="/cv-portfolio/assets/images/sentiment3.png" />

<img src="/cv-portfolio/assets/images/sentiment4.png" />

<img src="/cv-portfolio/assets/images/sentiment5.png" />

2.Implemented code for bag-of-word embeddings, topic analysis, Gradient Boosting classification and Bayesian Optimization and gained hands-on experience on NLP and text mining.  

3.Main contributor of project report and presentation slides.

<br/>

#### Project Findings: Why LDA Works?

We proposed a way to explain why topic features can improve the performance. In word2vec we used in baseline models, the vector of a center word was trained by the neighbor word pairs within a certain window. This training mechanism makes the created word vector incorporate the local semantic relations, and usually results in generated similar vectors with similar part-of-speech tagging. Thus, words with opposite polarity in sentiment can be clustered into the same group. However, compared to word2vec which incorporates more local information, the LDA algorithm incorporates more global statistical information because it assigns an undecided word to a topic whose words more frequently come along with the undecided word within all reviews, regardless of their positions in the reviews. And the pre-assigned seed words boost the prior probability more. From the feature importance of GBM , we found that all topic features were in the top, which is a further proof of the aforementioned limitation of word2vec and our good choices of pre-assigned words for guided LDA.

<p align="right"><a href="javascript:history.back()"><u>Back to Home</u></a></p>
