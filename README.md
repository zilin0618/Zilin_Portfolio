# Data Science Portfolio by Zilin Wang

This portfolio is a compilation of notebooks which I created for data analysis and exploration of machine learning algorithms. A separate category is for separate projects.

## Python Projects

### [1. Sales Analysis Project](https://github.com/zilin0618/Sales_Analysis)
This is a simple practice of EDA by using Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

I started by cleaning the data. Next, I move to the data exploration section, in this section 5 high level business questions were explored related to the data:
* What was the best month for sales? How much was earned that month?
<img src="https://github.com/zilin0618/Sales_Analysis/blob/master/Images/Sales_analysis1.JPG" width="600" height="300">
* What city sold the most product?
<img src="https://github.com/zilin0618/Sales_Analysis/blob/master/Images/Sales_analysis2.JPG" width="600" height="300">
* What time should we display advertisemens to maximize the likelihood of customer’s buying product?
<img src="https://github.com/zilin0618/Sales_Analysis/blob/master/Images/Sales_analysis3.JPG" width="600" height="300">
* What products are most often sold together?
<img src="https://github.com/zilin0618/Sales_Analysis/blob/master/Images/Sales_analysis4.JPG" width="600" height="300">
* What product sold the most? Why do you think it sold the most?
<img src="https://github.com/zilin0618/Sales_Analysis/blob/master/Images/Sales_analysis5.JPG" width="600" height="300">

To answer these questions many different pandas & matplotlib methods were applieed. Detailed Code can be found by click the title or [here](https://github.com/zilin0618/Sales_Analysis/blob/master/Zilin%20Sales%20Analysis%20Project.ipynb).

### [2. Customer Churn Project](https://github.com/zilin0618/Customer_Churn_Project)
Customer churn refers to the natural business cycle of losing customers. In this project the goal is to use data analytics techniques to help the company in characterizing its customer churn in order to predict which customers would churn in near future. Decision tree and Naïve Bayes classification algorithms were applied to compare machine learning models with different features.

I started by utilizing Python libraries to process over 3k raw data, and then cleaned up the data by eliminating missing values, duplicate values and unnecessary columns. After that, I conducted deep exploratory data analysis to identify important features, correlations, and analyzed customer behaviors based on different segments. A Decision Tree model and a Naïve Bayes model were build to classify customers that would churn in near feature. To evaluate the performance of two models Cross Validation method was applied, dataset was split into training and testing set, after comparison, the decision tree model had a better performance and achieved a 93% model accuracy.
Result of Decision Tree model:\
<img src="https://github.com/zilin0618/Customer_Churn_Project/blob/main/images/result.JPG" width="500" height="250">

Result of Naïve Bayes classification model:\
<img src="https://github.com/zilin0618/Customer_Churn_Project/blob/main/images/NB_result.JPG" width="500" height="250">

### [3. Yelp Recommendation System Project](https://github.com/zilin0618/YELP_recommender_system)
The objective of this project was to build a restaurant recommender system to provide a personalized restaurant recommendation.\
The datasets were downloaded from Yelp, which includes the datasets of the restaurant and user reviews.\
After data preprocessing, all necessary data were merged into one CSV file and then split into 70% training and 30 testing datasets. There are several approaches to build such system. This project shows several examples such as memory-based collaborative filtering (CF), model-based CF, and text-based CF techniques was applied to predict the rating or preference that a user would give to the restaurant. 
This project report can be seen [here](https://github.com/zilin0618/YELP_recommender_system/blob/main/CIND820_Final_Report.docx)

### [4. Online Retail Project](https://github.com/zilin0618/Online_Retail/blob/main/README.md)
The objective of this project was to extract Association Rules by using Frequent Patterm Mining algorithm (FPGrowth Tree).\
The detiled code can be seen [here](https://github.com/zilin0618/Online_Retail/blob/main/Online_Retail.ipynb).

Attribute Information:
* InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* Description: Product (item) name. Nominal.
* Quantity: The quantities of each product (item) per transaction. Numeric.
* InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
* UnitPrice: Unit price. Numeric, Product price per unit in sterling.
* CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* Country: Country name. Nominal, the name of the country where each customer resides.


## Tableau Project
### [Business Overview (Tableau Visualization)](https://public.tableau.com/app/profile/zilin.wang2962/viz/DailyBusinessOverviewReport/Dashboard1#1)
The objective of this project is to create an Tableau Dashboard to visualize the daily business data and the overview of business. 
Data Background: The dataset was obtained from two restaurants located in Shanghai, China. The dataset recorded their daily business information on the food delivery platforms, since the food delivery is one of the most popular ways of people getting their food.\
Attribute Information:
* GMV: Gross merchandise value (GMV) is the total value of merchandise sold over a given period of time. 
* 商家实收: The money that business owner actually get
* 曝光人数: Numbers of people who looked the store on the app page
* 进店人数: Numbers of unique people who clicked the store on the app page
* 下单人数: Numbers of unique people who placed orders in this store
* 商户补贴: Discount values that the restaurants provided
* 平台补贴: Discount values that the platforms provided
* CPC总费用: Total value of CPC (cost per click)

### DashBoard Illustration
<img src="https://github.com/zilin0618/Daily_Business_Overview_Tableau-/blob/main/Web%20capture_16-1-2022_14524_public.tableau.com.jpeg" width="750" height="900">

If you want to look at the detailed dashboard or play with the filter you can click the title or [here](https://public.tableau.com/app/profile/zilin.wang2962/viz/DailyBusinessOverviewReport/Dashboard1#1)

## Excel Project
### [Weekly Report](https://github.com/zilin0618/Weekly_Report_EXCEL)
The dataset was obtained from two restaurants located in Shanghai, China. The dataset recorded their daily business information on the food delivery platforms, since the food delivery is one of the most popular ways of people getting their food.The objective of this project is to create an Excel weekly report to visualize the weekly business data and the overview of business. 

In this project, functions such as 'sum', 'subtotal', 'sumif', 'sumifs', 'date', 'vlookup', 'index', and 'match' were used to do all the calculations. Functions of 'index' and 'match' were used primarily to automatically match the string of metrics on the report and then search on the source data. So that, the report can be done automatically for any weeks by changing the starting time. 
<img src="https://github.com/zilin0618/Weekly_Report_EXCEL/blob/main/weekly_report.JPG" width="550" height="700">
