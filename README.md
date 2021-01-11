# Data analysis of Google Play and iOS App Store

In this notebook, I analyzed apps available on Android and iOS platforms. The main goal was to analyze the market demand and find out what genres are most popular. This problem
could be considered as an simulation of particular data analyst task - imagine colleagues from AppDev team want to build app as succesfull as possible, so they want to know the most popular
app genres. To be more specific - at first, we want to explore free apps on the Google Play platform only. Then, we would pick the most popular genres and compare them with most popular genres
on App Store and ultimately decide what kind of app would have the best chance to succeed on the market.

Main purpose of creating such analysis was to get better feeling of data munging, as well as practice analytical thinking. Most important library used in the notebook is Python's Pandas.

**Steps I took in the notebook:**
1) Data cleaning and exploration - checking missing values, reformating table entries, etc.
2) Filtering data based on required conditions
3) Finding categories containing the most apps
4) Explore app genres by number of installs of particlar apps


**Data Used:**

[App Store](https://github.com/viliam-gago/data_analysis_popular_apps/blob/master/AppleStore.csv)

[Google Play](https://github.com/viliam-gago/data_analysis_popular_apps/blob/master/googleplaystore.csv)

Both dataset can be found on [Kaggle](https://www.kaggle.com/notebooks). Data is not actual - according to the source, they were scraped in 2017/2018.

**Main Notebook:**

[Analysis](https://github.com/viliam-gago/data_analysis_popular_apps/blob/master/data_analysis.ipynb)


