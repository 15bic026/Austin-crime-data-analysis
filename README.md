# Austin-crime-data-analysis

In this project, I dropped the rows containing null values as I was still left with 90% of the data after dropping those rows.

I created three new features using the original features of a dataset and then merged those features into the dataset, from these features I was able to extract some 
important insights for Austin Police Department.
The created features are as follows
1). Zip_Code_Crime_count: number of crimes as per the zipcodes
2). Clearance time: Number of days taken to solve the crime case.
3). Dangerous_Zip: 1 if the number of crimes in the zip code is greater than the median value, 0 otherwise.

![Austin crime 2](https://user-images.githubusercontent.com/77584094/228087425-2f4c7aca-e2aa-41b2-b683-ab67fbee1bd3.png)

I found that Inspector C has the highest average clearance time though having the second lowest number of cases involvement
![Austin crim3e3 ](https://user-images.githubusercontent.com/77584094/228089348-9619b4ed-e4ca-48f4-9d02-be9db7356f83.png)

During Exploratory data analysis I found that On week days the number of crimes are higher comaperd to weekends
![image](https://user-images.githubusercontent.com/77584094/228095969-3244e67b-9030-487a-918c-d68b8445aa28.png)

Out of the three created features I selected Dangerous_Zip as the target variable for the machine learning model to predict the crime rate of districts in Austin city. 
I deployed classification models Logistic Regression and Decision Tree along with hyper-parameter tuning 
and finally selected the model with best performance metrics.

![image](https://user-images.githubusercontent.com/77584094/228095324-a17a3298-16fd-45cd-bf91-95b21450750e.png)

I plotted the Austin map using GeoPandas to visualize which zipcodes fall under dangerous category and found that the central part of Austin is dangerous comaperd to the border parts of Austin compared to the 
number of crimes in each district and found an insight for people as well as Austin Police Department
![Screenshot 2023-03-25 225944](https://user-images.githubusercontent.com/77584094/228089617-d8ee8ebc-9875-4b37-adf6-afff0a516bbf.png)

