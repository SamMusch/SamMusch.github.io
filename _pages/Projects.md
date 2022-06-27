---
layout: archive
permalink: /projects/
title: "Sample of Projects Completed"
---



- Marketing Campaign Evaluation
  - [Kaggle Dataset](https://www.kaggle.com/bletchley/bank-marketing#balanced_bank.csv)
  - [Github Repository](https://github.com/SamMusch/Causal-Inference)
  - [Basic Tableau Plots](https://public.tableau.com/profile/sam.musch#!/vizhome/Causal_15841354400220/Dashboard1)


This repository includes the project our team performed for Causal Inference. Our dataset compared 2 marketing campaigns against a control group. We used a technique called "matching" to make sure that we were comparing people against those who were similar to them, and we also used a technique called "difference in difference" to evaluate how the campaigns differed after a surprise news story.



---


- Customer Forecasting
  - [Our Kaggle Post](https://www.kaggle.com/sammusch/kernel4ddef32243)
  - [Github Repository](https://github.com/SamMusch/Predictive-Project-Time-Series)

This was a project we completed for our course in Predictive Analytics (supervised learning) in Fall 2019. We were looking to forecast the number of daily visitors for 150 different restaurants located in different parts of Japan.

Our final model was an ensemble of RNN (sequential neural network model) and LightGBM (faster than XGboost to handle our large dataset).


---


- [Minneapolis Crime](https://github.com/SamMusch/Minneapolis-Crime)
- [Tableau Map](https://public.tableau.com/profile/sam.musch#!/vizhome/MinneapolisCrime/Sheet1)


This was the project our team completed for our course in Big Data in Fall 2019. We were looking to predict the number of crimes that would occur for each of the 5 police precincts on a daily level to help improve the number of people staffed on the day.

We used AWS services such as S3 for storage, Comprehend for sentiment analysis, and SageMaker to run our XGboost predictive model. We also used Tableau to dig deeper into the details of what had happened in the past and display geographic information. Our final model resulted in [25% average error](https://i.imgur.com/8ow32Gy.pnghttps://i.imgur.com/8ow32Gy.png) (MAPE), cutting the current intuition roughly in half.

My role specifically was to [clean existing police data](https://github.com/SamMusch/Minneapolis-Crime/blob/master/Data%20Cleaning%20and%20Features.ipynb), gather neighborhood data, and then combine them with daily Twitter sentiment and weather information. I also led the [model building](https://github.com/SamMusch/Minneapolis-Crime/blob/master/XGboost.ipynb) process.
