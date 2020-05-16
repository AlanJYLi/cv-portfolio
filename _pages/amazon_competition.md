---
title: "Master Data Science Challenge by Amazon"
permalink: /MDSC2020/
---

<img src="/cv-portfolio/assets/images/amazon600.png" />

### Weather Impact on Distribution Site Operations
<div style="color:#97AAC3">
  Group Project (4 persons) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Mar, 2020
</div>
*******************
  
  
#### Introduction
Master Data Science Challenge 2020 is a data science competition held by Amazon and Relational AI, facing students from any graduate-level program at Georgia Tech. The judges applied a rubric relying on 70% prediction accuracy / error, and 30% from creativity, process, and clarity of explanation. Our team won the **first place** (prize: $10,000) and was invited to present our Technical Report and have a Q&A session with key members of the Amazon Data Science team.  

The business problem of the competition is to build a model that determines the impact of weather on site operations. In detail, the dataset contains a response variable called Impact Score, created by Amazon data science team. The predictor variables are weather related parameters (around 100 parameters like wind speed, pressure, temperature, etc.) at zip5 level corresponding to each distribution facility. Historical data from Jan 1st, 2017 to Dec 31st, 2018 are provided, including 91 sampled facilities. The goal is to predicting daily Impact Score in 2019 of all these 91 distribution sites.  

#### Key Contributions and Highlights
1. Led the team to build the project framework and managed the project progress. 
2. Main contributor in data cleaning, EDA, feature engineering and model training.
   - Identified four operation patterns among all of the sampled distribution sites based on daily Impact Score, and proposed to conduct deck research and assign predicting values manually for closed sites and special sites.
   - Adopted Trewartha climate types as new features to augment the analysis and improved the model performance.
   - Proposed and implemented three approaches in modeling and indentified the best model: random forest regression with auto-regressor
