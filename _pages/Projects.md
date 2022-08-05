---
layout: archive
permalink: /projects/
title: "Sample of Projects Completed"
---


- Time Series Multivariate Deep Learning with LSTM
  - [Code in Google Colab](https://colab.research.google.com/drive/14Z3BsEq12YfcDTmO_OJi9YmiLhpm2bw_#scrollTo=29e2r-xyXrQN)
  - [Post on Linkedin](https://www.linkedin.com/posts/sammusch_google-colaboratory-activity-6949765780125204480-g7iX?utm_source=linkedin_share&utm_medium=member_desktop_web)
  - [Notes on LSTM](https://htmlpreview.github.io/?https://github.com/SamMusch/00-Data-Science/blob/main/TS%20Neural%20Networks.html)


This was a project I completed after taking a deep-dive into LSTMs. The objective is to predict daily household electricity consumption given 4 years of data.

---

- Time Series Multivariate Customer Forecasting
  - [Report with Code](https://htmlpreview.github.io/?https://github.com/SamMusch/Predictive-Project-Time-Series/blob/master/Predictive%20KT.html)
  - [Presentation Slides](https://docs.google.com/presentation/d/1bUKSU8vLlv2M4-dflHaJGDqiRqiWalr-/edit?usp=sharing&ouid=111023174892277357363&rtpof=true&sd=true)
  - [Github Repository](https://github.com/SamMusch/Predictive-Project-Time-Series)


This was a project we completed for our course in Predictive Analytics (supervised learning) in Fall 2019. We were looking to forecast the number of daily visitors for 150 different restaurants located in different parts of Japan. Our final model was an ensemble of RNN (sequential neural network model) and LightGBM (faster than XGboost to handle our large dataset).

---

- Marketing (A/B Testing, Multivariate Causal Inference)
  - [Final Report with Code](https://htmlpreview.github.io/?https://github.com/SamMusch/00-Data-Science/blob/main/Marketing%20Causal%20Analysis.html)
  - [Kaggle Dataset](https://www.kaggle.com/bletchley/bank-marketing#balanced_bank.csv)

This repository includes the project our team performed for Causal Inference. Our dataset compared 2 marketing campaigns against a control group. We used a technique called "matching" to make sure that we were comparing people against those who were similar to them, and we also used a technique called "difference in difference" to evaluate how the campaigns differed after a surprise news story.


---

- Minneapolis Crime
  - [Github](https://github.com/SamMusch/Minneapolis-Crime)
  - [Tableau](https://public.tableau.com/profile/sam.musch#!/vizhome/MinneapolisCrime/Sheet1)


This was the project our team completed for our course in Big Data in Fall 2019. We were looking to predict the number of crimes that would occur for each of the 5 police precincts on a daily level to help improve the number of people staffed on the day.

We used AWS services such as S3 for storage, Comprehend for sentiment analysis, and SageMaker to run our XGboost predictive model. We also used Tableau to dig deeper into the details of what had happened in the past and display geographic information. Our final model resulted in [25% average error](https://i.imgur.com/8ow32Gy.pnghttps://i.imgur.com/8ow32Gy.png) (MAPE), cutting the current error in half.
