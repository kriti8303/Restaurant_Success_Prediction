# Restaurant_Success_Prediction
## Dataset link :
https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants
## Description of the dataset : 
The dataset consists of 51717 rows and 17 columns. Column Description : url : Contains the url of the restaurant in the Zomato website. address : Contains the address of the restaurant in Bangalore. name : Contains the name of the restaurant. online_order : Whether online ordering is available in the restaurant or not. book_table : Table book option available or not. rate : Contains the overall rating of the restaurant out of 5. votes : Contains the total number of rating for the restaurant as of the mentioned date. phone : Contains the phone number of the restaurant. location : Contains the neighbourhood in which the restaurant is located. rest_type : Restaurant type. dish_liked : Dishes people liked in the restaurant. cuisines : Food styles, seperated by comma. approx_cost(for two people) : Contains the approximate cost for a meal for two people. reviews_list : List of tuples containing reviews for the restaurant, each tuple consists of two values, rating and review by the customer. menu_item : contains list of menus available in the restaurant. listed_in(type) : type of meal. listed_in(city) : Contains the neighbourhood in which the restaurant is listed.
## In this project, we will analyze the Zomato Bangalore Restaurants dataset. For this we will:

1. Get intuition about the data
2. Do an exploratory data analysis
3. Use graphical modules to visualize the data
4. Apply a predictive point of view for helping people to choose the best restaurant.
5. Using this predictive approach for predicting the success of a new restaurant in Bengaluru.
6. Data Preprocessing : Our data consisted of quite a few null values. To solve the problem of missing values, we followed the following steps : (i) First we removed all rows containing null values in the ‘cuisines’ column. (ii) For the second step, since the ‘address’, ‘phone’, ‘url’, ‘listed_in(city)’ columns had a lot of null values, we dropped these 4 columns. (iii) The third step was renaming the ‘approx_cost(for two people)’ and ‘listed_in(type)’ columns as ‘average_cost’ and ‘listed_type’

After performing a few visualizations to understand our data better, we split the data into 80% training data and 20% test data. Next, we used Machine Learning models to fit the data.

The main goal here is to predict the success (in terms of rate) for new restaurants put in Zomato service. This is very interesting for business areas to evaluate the main concepts of restaurants and customers preferences in Bengaluru region. Also, it's helpful for new restaurants to analyze their business model and features before launching them!
