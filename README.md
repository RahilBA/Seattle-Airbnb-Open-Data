# Blog Post Airbnb Seattle
### Writing a Data Science blog post for Udacity DSND project 

### Overview
This project is part of Udacity's Data Science Nanodegree course. This repository includes the python codes to answer three questions about Airbnb in Seattle following the CRISP-DM process. The link to the blog post is [here](https://medium.com/@rahil.bagheri/using-data-to-help-seattle-airbnb-hosts-and-guests-make-smarter-decisions-39749cc43ae). 

The project is following the CRISP-DM process including:

1) Business Understanding
2) Data Understanding
3) Data Preparation
4) Modeling
5) Evaluation
6) Deployment

### Business understanding 
Airbnb provides an excellent solution to short term accommodations. But it is time to use data and guide the new hosts to estimate more reasonable prices while maximizing their revenue. Also, help guests to know which accommodation factors they should pay more attention to save some money.I tried to focus on answering questions that might help both sides since every single of us can be both a host or guest. 

### Data understanding
The Seattle AirBnB data can be found [here](https://www.kaggle.com/airbnb/seattle). There are 3 differnt csv data files:
1) Listings, including full descriptions and average review score  
2) Reviews, including unique id for each reviewer and detailed comments  
3) Calendar, including listing id and the price and availability for that day




### Motivation 
For this project, I was intersected in answering the following questions:
1) Which AirBnB listing is more profitable?
2) How the price rates change based on each listings' feature?
3) Forcast the price rates for future months, for example Jan or Feb 2017?

### File Description
These 3 questions are analyzed and answered through 3 different notebooks. Each file includes data preprocessing, data formatting, visualization, descriptive statistics and predictive analysis. But the focus of this study was to follow CRISP-DM process and communicate the result through a blog post than developing the best predictive solution. The developed functions and libraries are repeated within each notebook if necessary.

### Results
As mentined before, the result and findings are communicated through a blog posted on Medium and can be found here.

### Installment
1) Sklearn 
2) Prophet: Prophet is a procedure introduced by Facebook for forecasting time series data based on additive model where nonlinear trends are fit with daily, weekly and yearly seasonality plus holidays. You can read more about Prophet [here](https://facebook.github.io/prophet/).
3) numpy
4) seaborn
5) datetime
6) calendar

### Acknowledgement
Must give credit to Udacity awesome Data Science course for good course contents and projects, and to Kaggle for the data.Please feel free to use these codes and develop them if you are interested. 

### Resources
more details about SMOTE with Imbalance Data can be found [here](https://www.kaggle.com/qianchao/smote-with-imbalance-data) and [here](https://www.kaggle.com/rafjaa/resampling-strategies-for-imbalanced-datasets)
