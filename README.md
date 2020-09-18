# Udacity Capstone Project
## Title:
Machine Learning Algorithms for Football Prediction using statistics from Brazilian championship data

## Abstract: 
This article evaluated football/Soccer results (victory, draw, loss) prediction in Brazilian Football Championship using various machine learning models based on real-world data from the real matches. The models were tested recursively and average predictive results were compared. The results showed that logistic regression and support vectors machine yielded the best results, exhibiting superior average accuracy performance in comparison to others classifiers (KNN and Random Forest), with 49.77\% accuracy (logistic Regression), almost 17\% better than a randomly decision (benchmark) which had 33\% of success chance. In addition, a ranking of the features' relative importance was made to orient the use of Data.

## Motivation: 
Apllying Machine Learning tecniques on Football results prediction, in order to understand the data and evaluated the difficulty level of prediction.

## Libraries:
In this section all libraries will be detailed and in witch files they are.

* Pandas: Treatment of DataBase. Used in Webscrapping and Treatment Files.
* Numpy: Treatment of DataBase. Used in Treatment File.
* Seaborn: Plot graphs and images. Used in Treatment File.
* Beautifull Soup: Plot graphs and images. Used in Webscrapping File.
* Matplotlib.pyplot: Plot graphs and images. Used in Treatment File.
* Xlsxwriter: Write the Database extracted in excel file. Used in Treatment File.
* Os: Easy access files inside a folder of the memory computer. Used in Webscrapping File.
* Requests: Allows send HTTP/1.1 requests. Used in Webscrapping File.
* Time: Show the running time of some algorithms. Used in Webscrapping File.

## Summmary of Results
![Results](/images/results.png)


## Files:

In this section all files will be described.

* WebScrapping: Contains all the functions used to web scrapp the page of FBREF
* Tratament: Contains all the treatment of the Database used.
* UDACITY_CAPSTONE_PROJECT: PDF post of Udacity Capstone project.
* Brasileirao: Data Base from brazilia Championship futbool.


## References and Sources of Data:

* https://fbref.com/ : Site where Webscrapping was done - Data from Brazilian Serie A Fotball.
