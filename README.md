# Data Science Portfolio
Data Science Projects



## [Clustering College Degrees to Explore Salary Outcome](https://github.com/Rlegaspi562/Clustering-College-Degrees-to-Explore-Salary-Outcomes/blob/master/FINAL%20Exploring%20Salary%20Outcomes%20of%20College%20Degrees%20using%20K-Means%20Clustering.ipynb)
### **Project Goal:** 
Clustering to see how undergraduate degrees compare in terms of salary over time using K Means clustering in R. 
### Data Description:
The data used in this notebook is collected from a year-long survey of 1.2 million people with only a bachelor's degree by PayScale Inc., made available by the Wall Street Journal for their article Ivy League's Big Edge: Starting Pay (note this is from 2008).
### Findings:

### * The liberal arts cluster, although may be the lowest and somewhat riskiest majors the upside can be limitless. Also a good question to ponder on is that these majors are typically popular and mainly dominated by among women.

![](/images/clustthree.PNG)

##### * The In-Between cluster, as we can see is right in the middle but we can begin to see the higher percentile ranges to reaching higher and higher especially for finance and marketing majors.

![](/images/clustone.PNG)

##### * Lastly, the Over Achievers cluster, typically math, science, and engineering based start and end careers off at the highest salaries, but then again is it surprising? Also, might be worth exploring why these fields pay so much and why it is typically male dominated as well.

![](/images/clusttwo.PNG)

* Two careers tied for the highest career percent growth: Math & Philosophy.

##### Keep in mind one's financial destiny will certainly be influenced by numerous other factors including the school attended, location, passion or talent for the subject, and of course the actual career pursued.


## [Sentiment Analysis of Yelp Reviews: Project Overview](https://github.com/Rlegaspi562/Visualization-of-Sentiment-Analysis-of-Yelp-reviews)
### Project Goal:
In this small project I'm curious to see what reviews say about a nearby ramen shop I frequent. I do basic sentiment/text analysis and try to extract some basic visuals I think would be interesting to see from text reviews I scrape from Yelp using R.
### Data Description:
This data has been scraped from yelp.com for educational/analytical purposes and consists of 315 observations with one variable: Reviews.

### Findings:

#### Word Cloud (The more frequent the word, the bigger)

![](/images/YelpCloud.png)

#### Frequency of Positive & Negative Sentiment

![](/images/posnegfreq.PNG)

#### Top 10 words Contributing to Positive & Negative Sentiment

![](/images/top10contribtoposneg.PNG)

#### Top 15 Bigrams of Silverlake Ramen Reviews

![](/images/top15bigrams.PNG)


## [Analyzing International Debt Statistics](https://github.com/Rlegaspi562/Analyzing-International-Debt-Statistics/blob/master/notebook.ipynb)
### Project Goal: 
To gain better familiarity and apply SQL queries to answer and gain insights from data 
### Data Description:
This data is from [The World Bank](https://www.worldbank.org/) connecting to the "international_debt database" using postgreSQL.  

### Findings:

* There are these things called debt indicator codes which specifiy the type debt a country has.
* The number of distinct countries the owe are 124.

### **The country with the highest amount of debt at the time of doing this project was China**

![](/images/highestdebt.PNG)

### **Total Amount of Debt Owed by Countries**

![](/images/totaldebt.PNG)


##### Keep in mind one's financial destiny will certainly be influenced by numerous other factors including the school attended, location, passion or talent for the subject, and of course the actual career pursued.


## [Early COVID-19 Visualization in R](https://github.com/Rlegaspi562/COVID-19-Visualization-in-R/blob/master/notebook.ipynb)
### Project Goal: 
In this project I visualize COVID-19 data pulled on March 17, 2020.
### Data Description:
The [raw data](https://github.com/Rlegaspi562/COVID-19-Visualization-in-R/tree/master/datasets) pulled and arranged by the Johns Hopkins University Center for Systems Science and Engineering (JHU CCSE).

### Findings:

* The number of new COVID-19 Cases are increasing at an exponential rate.
* Whilst China was reaching its apex, the rest of the world was slowly increasing at an exponential rate.
* Politcal decisions and the way countries report its data play significant roles in the increase of new cases.
* At the time of the release of this data, not all countries are hit equally and should observe the rate it is affecting countries such as Italy, Iran, and South Korea.

![](/images/COVID.png)


## [Machine Learning to Predict Diabetes: Project Overview](https://github.com/Rlegaspi562/multiple-logistic-regression-to-predict-diabetes/blob/master/_Pt%204%20logistic%20regression%20to%20predict%20diabetes.ipynb)
### Project Goal:
As an introduction to data science and to apply my currently learned skills, this project was culminated. The goal of this project is to go through the data science life cycle applying fundamental techniques to a subject topic that I've been curious of - predicting heart disease. Throughout this project I use a basic **data science life cycle and ML pipeline**: - Data cleaning - Exploratory data analysis - Hypothesis testing (chi-square / t-test) - Data modeling - Data analysis of results  This project has allowed me to simply apply what I have learned using **multiple logistic regression** model in R. 
### Data Description:
The Pima Indians Diabetes dataset was obtained from [Kaggle](https://www.kaggle.com/kumargh/pimaindiansdiabetescsv) containing 768 observations/cases and 9 variables as biological characteristics.  

![](/images/DiabetesCorrelogram.png)

