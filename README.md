# Austin-crime-data-analysis

In this project, I dropped the rows containing null values as I was still left with 90% of the data after dropping those rows.

I created three new features using the original features of a dataset and then merged those features into the dataset, from these features I was able to extract some 
important insights for Austin Police Department

Out of the three created features I selected one feature as the target variable for the machine learning model to predict the crime rate of districts in Austin city. 
I deployed various classification models like Logistic Regression, Decision Tree, SVM, Random Forest Classifier, XgBoost Classifier along with hyper-parameter tuning 
and finally selected the model with best performance metrics.

I plotted various charts using Seaborn and Matplot lib to visualize the findings and insights, moreover, I also plotted the Austin map using GeoPandas to visualize the 
number of crimes in each district and found an insight for people as well as Austin Police Department
