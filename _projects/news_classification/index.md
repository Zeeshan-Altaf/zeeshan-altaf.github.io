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

main-image: /poster.png
---

---
{% include image-gallery.html images="_projects/news_classification/CRIME_headline.jpg" height="400" %} 
{% include image-gallery.html images="_projects/news_classification/EDUCATION_headline.jpg" height="400" %}
{% include image-gallery.html images="_projects/news_classification/U.S. NEWS_headline.jpg" height="400" %}
{% include image-gallery.html images="_projects/news_classification/WORLD NEWS.jpg" height="400" %}
place the images in project folder/images then update the file path.   

