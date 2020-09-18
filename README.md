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

As it can be seen in the table bellow, the algorithm achieved almost 50% of accuracy, considering that the random prediction probability of success is 33\% (Victory/Draw/Loss), it is a good signal, it shows that the algorithm was able to identify some patterns after all.

![results](https://github.com/Matheuskempa/My_Udacity_Capstone/blob/master/results.PNG?raw=true)

After all 1000 times the Logistic Regression had the best results, with one of the lowest standard deviation rates and the highest accuracy between all four models. SVM performed better than the others, but had the highest standard deviation, maybe showing that the model tends to vary more than other models.

## Conclusions

This project proves that football prediction is still a very hard task, at least with only this variables, ans it still needs more variables to help on the prediction of the results. However we can see by this article that a machine learning algorithms can already "think" on which team bet an can still be more accurate than people that does not know about the games having almost 17\% of advantage in the prediction when comparing to the probability of a randomly prediction.

For the future i suggest to investigate and find more variables that could be usefully, as injuries for example, or more details of the players of each team, maybe FIFA or PRO EOVLUTION GAME data could help to bring more information to inside of the DataBase. Another thing that could be done for the future is on predicting the number of goals for of each team, this is more complex because it depends of the results predicted and they must conciliate with it, for example: it couldn't be two goals for the home team and two goals for the way team if the result was predicted as victory of the home team. So, maybe, this article can be a source of inspiration to the creation of better and complex models in the future.


## Files:

In this section all files will be described.

* WebScrapping: Contains all the functions used to web scrapp the page of FBREF
* Tratament: Contains all the treatment of the Database used.
* UDACITY_CAPSTONE_POST: PDF post of Udacity Capstone project.
* Brasileirao: Data Base from brazilia Championship futbool.
* Results: PNG file with the results


## References and Sources of Data:

* https://fbref.com/ : Site where Webscrapping was done - Data from Brazilian Serie A Fotball.
