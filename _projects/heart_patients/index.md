---
layout: post
title: Predicting outcome (fatal & non-fatal) of heart attack patients within 72 hours of hospital admission
description: In this project I focuses on predicting fatal outcomes within 72 hours of hospital admission in patients suffering from myocardial infarction (MI), commonly referred to as a heart attack. The objective is to discover patterns and risk factors associated with early mortality using machine learning model trained on clinical and diagnostic features. I used R programming language to analyze, visualize and for training the model. Handeled dataset imbalance by using resampling technique (up-sampling & down-sampling). Random forest and XGBoost were implemented, XGBoost outperformed random forest and achieved 77.3% It not only yields superior performance on imbalanced multiclass outcomes but also maintains consistency in identifying high-risk clinical indicators.

skills: 
  - Machine learning
  - Data cleaning
  - Feature engineering
  - Data modelling
  - Fine tuning
  - Data visualization

main-image: /CRIME_headline.jpg
---

---
{% include image-gallery.html images="/outcome_distribution.png" height="400" %}
**~85% of the patients survived (LET_IS = 0) after 72 hours of being admitted to hospital, indicates high outcome class imbalance.**
{% include image-gallery.html images="/age_var.png" height="400" %}  {% include image-gallery.html images="/U.S. NEWS_headline.jpg" height="400" %}
**Most of the patients aged between 55-75 and it is evident that this age group is more prone to heart attack.**
{% include image-gallery.html images="/imp_features.png" height="400" %}
**Top 5 most important features for predicting the outcome class in XGBoost.**
