# Linear Regression
## Prediction of test score

Business problem: Prediction of test score of students based on their study hours

Data Collection: Received the structured data during internship with two columns of no of hours and marks and saved it in dataframe

Data Preparation: Using describe command, I got to know about the spread of dataset and its IQR and Std. Calculated z-score of the each value in scores and hours dataset and find the upper and lower limit with 95% confidence interval, which gave some insights about the dataset.
Then I started visualization of the dataset, using heatmap and pairplot(scatter) and concluded the relation between the given dataset and it was straight line and that's how I came to conclusion of using Linear Regression Model here.

Choose a model: I chose Linear Regression model here

Train the model: Splitted the dataset into two sets: Train and Test datasets using test_train_split and kept 30% data in test dataset and then train the model after importing from sklearn. Fit the model with train dataset and calculate the intercept and slope which I used for make predictions using test dataset. Finally I have test and prediction datas.

Evaluate the model: Calculated the Root mean square error(RMSE) and it was acceptable which validate our model

Make Predictions: With the evaluated model, now I can make prediction and solve the given business query.
