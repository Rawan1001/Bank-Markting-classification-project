# Bank- Markting-classification-project
> In this project our task was to get a dataset to build a classification model on. We choose to analysis a data set of a bank to determine if the customers will subscribe to a service the bank is offering. Our target will be (yes or no), as a result, the type of the model we will build is a binary classification model. The dataset will be obtained from the uci.edu website and will consist of 45212 rows and 17 columns in total.
- https://archive.ics.uci.edu/ml/datasets/bank+marketing
## The Approach:
analyzing the dataset using EDA techniques.
Building a classification model to predict the people who are most likely to subscribe to the service the bank is offering.

### Classification:
___
> Here we used 6 types of classification models, and the table below compares between them according to :
> Accuracy, F1, Precision, Recall, and ROC Score.

| Model                 | Accuracy | F1    | Precision  | Recall  | ROC  |
|:----                  |:-------: |:-----:|:----------:|:-------:|----: |
| LogisticRegression    | 0.8658   |0.5247 |0.4580	    |0.6141	  |0.7572|
| KNeighborsClassifier  | 0.7763   |0.3531 |0.2711	    |0.5060	  |0.6597|
| RandomForestClassifier|0.8983    |0.5267 |0.6002	    |0.4693	  |0.7132|
| DecisionTreeClassifier|0.8674    |0.4395 |0.4485	    |0.4308	  |0.6791|
| XGBClassifier         |0.8853    |0.5909 |0.5187	    |0.6865	  |0.7996|
| BaggingClassifier     |0.8944    |0.5497 |0.5660	    |0.5344	  |0.7391|

##### Result & notes:
___
> - The model which gave us the highest scores in both the training and validation sets are the Logistic Regression model with an accuracy score of 82% and 83% respectively.
> - In the test set the Logistic Regression gave us 86%, which is even better than the scores of the training and the validation sets. 
> - last, we were able to Deploy our model to the website flask and predict the results according to the chosen features.
