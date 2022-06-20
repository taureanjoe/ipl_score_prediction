# IPL First Innings Score Prediction
A simple machine learning model to predict IPL first innings score

This is a IPL score prediction model using Ridge regression which is an upgraded form of linear regression.

### Prerequisites
You must have Scikit Learn, Pandas (for Machine Leraning Model) and Flask (for API) installed.


I also tried Linear regression but that was overfitting to the next level, that’s why I went with Ridge Regression because it prevents our model from overfitting.

Lasso was also giving similar results

![image](https://user-images.githubusercontent.com/74256522/174554487-d0a4daa5-60d8-47b7-a459-a37eafb78338.png)

* In our specific use case features like mid, batsman, bowler, striker, and non-striker would not play a great role so it’s better to drop them.
* I know that batsmen can play a role in changing scores, but the problem is that there are tonnes of batsmen that have played in IPL so we can’t operate on these many categories, so it’s better to drop them.
