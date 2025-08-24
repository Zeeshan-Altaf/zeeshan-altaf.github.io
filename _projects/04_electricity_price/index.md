---
layout: post
title: Forecasting electricity price of Australia using time series analysis
description: The demand for electricity and its associated costs plays a critical role in shaping national energy policy, business operations, and household economics. In this project, I focuses on applying predictive analytics techniques to historical electricity pricing data to forecast Australia’s average electricity prices through to the year 2050. The dataset, covering state-level electricity prices from 1998 to 2025, is used to analyze trends and derive forward-looking insights. Linear regression and ARIMA are implemented using R. Overall, ARIMA performed well as it incorporates both recent price changes and overall trend, making it more accurate for non-stationary time series forecasting. It predicts more realistic growth of above $200/MWh for year 2050. •	Multiple ARIMA configurations were tested (e.g., (1,1,0), (1,1,1)). The final model ARIMA (0,1,1) with drift was selected based on lowest AIC.

skills: 
  - Predictive analytics
  - Data pre-processing
  - Feature engineering
  - Data Visualization

main-image: /elec_poster.jpg
---

---
{% include image-gallery.html images="/forecasting.jpg" height="400" %}
**Forecasting of national average price of Australia from 2025 to 2050. Forecasting is based on historical data (1999-2025), linear regression and ARIMA is used.**  
{% include image-gallery.html images="/lin_arima_comp.jpg" height="400" %}  {% include image-gallery.html images="/U.S. NEWS_headline.jpg" height="400" %}
**Performance comparison of linear regression and ARIMA.**  

