# Austin-crime-data-analysis

In this project, I dropped the rows containing null values as I was still left with 90% of the data after dropping those rows.

I created three new features using the original features of a dataset and then merged those features into the dataset, from these features I was able to extract some 
crucial insights for Austin Police Department.
The created features are as follows

1). Zip_Crime: number of crimes as per the zipcodes

2). Clearance time: Number of days taken to solve the crime case.

3). Dangerous_Zip: 1 if the number of crimes in the zip code is greater than the median value, 0 otherwise.


I have plotted a bar chart to visualize the distribution of crimes across the zipcodes of Austin city
![Austin crime 2](https://user-images.githubusercontent.com/77584094/228087425-2f4c7aca-e2aa-41b2-b683-ab67fbee1bd3.png)






I have calculated the Average clearance time and plotted subplots to compare the clearance time and Number of involvements in Crime cases for each inspector(Dis_APD)
![image](https://user-images.githubusercontent.com/77584094/228101473-c3172eb5-80fd-4d09-a7c1-d9222cf5c513.png)
From the above plot, I found that Inspector C has the highest average clearance time though having the second lowest number of cases involvement



During Exploratory data analysis I found that On week days the number of crimes are higher comaperd to weekends 
![image](https://user-images.githubusercontent.com/77584094/228095969-3244e67b-9030-487a-918c-d68b8445aa28.png)

In the above plot, it is clear that the trend is decreasing, starting from Monday to Sunday





Out of the three created features I selected Dangerous_Zip as the target variable for the machine learning model to predict the crime rate of districts in Austin city. 
I deployed classification models Logistic Regression and Decision Tree along with hyper-parameter tuning 
and finally selected the model with best performance metrics.

I have plotted a confusion matrix to visualize the performance of the model on test data
![image](https://user-images.githubusercontent.com/77584094/228095324-a17a3298-16fd-45cd-bf91-95b21450750e.png)

The above confusion matrix shows the model performance and the model accuracy is 81.25%



I have plotted the Austin map using GeoPandas to visualize which zip codes fall under the dangerous category and found that the central part of Austin is dangerous compared to the border parts of Austin compared to the number of crimes in each district and found an insight for people as well as Austin Police Department

![Screenshot 2023-03-25 225944](https://user-images.githubusercontent.com/77584094/228089617-d8ee8ebc-9875-4b37-adf6-afff0a516bbf.png)

