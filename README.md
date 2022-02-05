# Customer-Segmentation

Customer segmentation is the practice of dividing 
a company's customers into groups that reflect 
similarity among customers in each group. 
The goal of segmenting customers is to decide 
how to relate to customers in each segment in 
order to maximize the value of each customer to 
the business.

Here, I will apply clustering algorithm to segment the customers.


**Below are the summary of the project:-**

1.We have a dataset of 541,908 rows and 8 columns.

2.The dataset contains transactions occurred between 01/12/2010 and 09/12/2011.

3.The dataset contains ‘Null’ values of 132,220 rows, which we have dropped. After dropping the dataset contains 397,884 rows.

4.Then we performed Exploratory data analysis. Through EDA, we came to know that the dataset contains total of 37 countries, where UK tops the list with 300k+ invoices and Saudi Arabia at the bottom with only 9 invoices.

5.The most selling products are ‘White Hanging heart T-light holder’, ‘Regency Cake Stand’ and ‘Jimbo bag red retrospect’

6.When analyzed based on hourly bases, noon session is where most invoices generated, particularly between 12 PM and 3 PM

7.When analyzed based on day, ’Thursday’ is  the most invoices generated day.

8.When analyzed based on month, ’November’ month is the most invoice generated month.

9.Then, we applied Recency, Frequency and Monetary value metrics

10.We given number ‘1’ for best score and ‘4’ for worst score in RFM metrics

11.Based on RFM, the count of best customers are 440, Loyal customers are 1080, Aggressive spenders are 1085, Almost lost customers are 165 and Lost customers are 385.

12.For applying the model, the dataset must be symmetrical in shape for good results, when we look at distribution plot of our data, it was rightly skewed so we introduced Log transformation to result in symmetrical data.

13.For data transformation, we used Standard scaler transformation.

14.Then, we used Elbow method to determine number of optimal clusters. Which gave as cluster value-4.

15.By using k-means clustering, we were able to segment the customers in to 4 groups.




