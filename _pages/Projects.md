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

---

- [Undergrad - Stedman's Cafe](https://github.com/SamMusch/Stedmans)

This was an undergraduate project for our class on Economics in industry ([My notes](https://github.com/SamMusch/Industrial-Organization)). Our client was the cafe in our Business Administration building. This was an open-ended project and was the first time I had really gone through the process of identifying a use case and using analytics to solve a problem.

At the time of this project I was still a beginner in R and was in the process of learning Tableau so I see many things now that I would have done differently. Our chosen use case ultimately was to identify and promote high profit margin items.

[Images produced with ggplot](https://imgur.com/a/G0LVvah)  
[Data cleaning process - R file](https://github.com/SamMusch/Stedmans/blob/master/Stedman2.R)

*Tableau Public Workbooks - These were made public so that members of the cafe staff would be able to reference them.*  
[Annual Summary](https://public.tableau.com/profile/sam.musch#!/vizhome/Summary_15514603349400/DashboardSummary)  
[Category Breakdown](https://public.tableau.com/profile/sam.musch#!/vizhome/CategoryBreakdown_15557600432150/MealFoodCatBreakdownTopItems50)  
[Volume by Hour](https://public.tableau.com/profile/sam.musch#!/vizhome/VolumebyHour/VolumeDash)  
[Item Profit Margins](https://public.tableau.com/profile/sam.musch#!/vizhome/StedmansProfitMargin/MarginCat)  


---

- [Undergrad - Econometrics, Agriculture Wages](https://github.com/SamMusch/R/blob/master/Projects/Econometrics.R)

This was an undergraduate project for my course on Econometrics. This was my very first introduction to R, so almost all of the code is statistical tests. The focus of the project was to run multiple regression and check for multicollinearity, normality of residuals, etc.

[Tableau Dashboard](https://public.tableau.com/profile/sam.musch#!/vizhome/AgricultureWages/Dashboard1)


---


*The two following semester projects are not included as we have an NDA with the companies we worked with.*
- Client: Mall of America (Exploratory Analytics)
  - Saved est $5M / year with predictive model to optimize number of hourly staff
  - Built user-adjustable Tableau heatmap to improve staff location within mall
- Client: Leading Hospitality and Entertainment Business
  - Increased revenue by est $1.4M / month by identifying high value customers and reducing attrition
  - Used clustering, decision trees, Poisson Regression to identify these customers
  - Led team in creating visualizations and transfer documents to keep technical info clear
