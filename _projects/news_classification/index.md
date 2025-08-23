---
layout: post
title: Multi-class news categorization by fine tuning pre-trained large language models (LLMs)
description:  In this project I have created a tool to effectively categorize news articles given their headlines. Comparative analysis of DistilBERT, DistilBART, RoBERTa, and DistilGPT-2 revealed the superior perormance of DistilBART due to its higher number of learnable paramenters (~230 M). DistilBART achieved 66.3% with 42 labels of news article. Models performance were restricted due to dataset imbalance and overlapping categories. After merging overlapping categories, DistilBART achieved the accuracy of 71.0%. 
skills: 
  - Natural language processing
  - Large language models
  - Fine tuning
  - Data cleaning
  - Exploratory data analysis
  - Data visualization

main-image: /CRIME.jpg
---

---
{% include image-gallery.html images="/CRIME_headline.jpg" height="400" %}  {% include image-gallery.html images="/U.S. NEWS_headline.jpg" height="400" %}
**World Cloud Analysis of two categorize (CRIME & U.S.NEWS) reveals the ovelapping nature of dataset.**
{% include image-gallery.html images="/dataset_distribution_42.jpg" height="400" %}
**Among 42 categories, Entertainment, Politics and Wellness accounts for more than 30% of the data which leads to imbalance distribution.**  
{% include image-gallery.html images="/test_accuracy_21.jpg" height="400" %}
**Test accuracy of DistilBART with 21 categories**
