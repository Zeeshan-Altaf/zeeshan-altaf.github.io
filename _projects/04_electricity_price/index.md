---
layout: post
title: Forecasting electricity price of Australia using time series analysis
description: The demand for electricity and its associated costs plays a critical role in shaping national energy policy, business operations, and household economics. In this project, I focuses on applying predictive analytics techniques to historical electricity pricing data to forecast Australia’s average electricity prices through to the year 2050. The dataset, covering state-level electricity prices from 1998 to 2025, is used to analyze trends and derive forward-looking insights. Linear regression and ARIMA are implemented using R. Overall, ARIMA performed well as it incorporates both recent price changes and overall trend, making it more accurate for non-stationary time series forecasting. It predicts more realistic growth of above $200/MWh for year 2050.

skills: 
  - Predictive analytics
  - Data pre-processing
  - Feature engineering
  - Data Visualization

main-image: /CRIME_headline.jpg
---

---
{% include image-gallery.html images="/dataset_distribution_42.jpg" height="400" %}
**Among 42 categories, Entertainment, Politics and Wellness accounts for more than 30% of the data which leads to imbalance distribution.**
{% include image-gallery.html images="/CRIME_headline.jpg" height="400" %}  {% include image-gallery.html images="/U.S. NEWS_headline.jpg" height="400" %}
**World Cloud Analysis of two categorize (CRIME & U.S.NEWS) reveals the ovelapping nature of dataset.**
{% include image-gallery.html images="/test_accuracy_21.jpg" height="400" %}
**Test accuracy of DistilBART with 21 categories, achieving 71.0% accuracy.**
