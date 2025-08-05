# Product-Purchased-or-not-

In this project, I took a data set which had 3 input columns - Gender, Age and EstimatedSalary, using which I trained a model that would predict whether a person would buy the product or not. For this, I created a Logistic Regression model in which I did OneHotEncoding in Gender and StandardScale the EstimatedSalary so that the model would have to do fewer calculations. After training the model, when its accuracy_score was calculated, it was 90% which I then validated using cross_val_score.
