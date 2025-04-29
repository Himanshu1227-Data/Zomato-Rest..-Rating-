# Zomato-Rest..-Rating-
Zomato-Bangalore-Restaurants Analysis and Model Deployment
Introduction
The Zomato-Bangalore-Restaurants dataset provides insights into various factors affecting the establishment and popularity of different types of restaurants in Bangalore. In this project, we conduct exploratory data analysis (EDA) to understand trends in restaurant offerings, cuisines, pricing, and location concentrations. Additionally, we develop machine learning models to predict restaurant performance based on the dataset attributes. Finally, we deploy our best-performing model using Streamlit, allowing users to interactively explore predictions and insights.

Data Description
The dataset consists of several features that describe different aspects of restaurants in Bangalore:

url: URL of the restaurant on the Zomato website \n
address: Address of the restaurant in Bengaluru
name: Name of the restaurant
online_order: Availability of online ordering
book_table: Availability of table booking
rate: Overall rating of the restaurant out of 5
votes: Total number of ratings for the restaurant
phone: Phone number of the restaurant
location: Neighborhood where the restaurant is situated
rest_type: Type of restaurant
dish_liked: Dishes liked by customers
cuisines: Food styles offered, separated by commas
approx_cost(for two people): Approximate cost for a meal for two people
reviews_list: List of tuples containing ratings and reviews by customers
menu_item: List of menus available in the restaurant
listed_in(type): Type of meal offered
listed_in(city): Neighborhood where the restaurant is listed
Exploratory Data Analysis (EDA)
Popular Voted Restaurants: Identifying the most popular restaurants based on votes.
Top 10 Cuisines: Determining the top 10 popular cuisines offered by Bangalore restaurants.
Expensive Restaurant Types: Identifying the top 10 expensive restaurant types on average.
Restaurant Concentration by Location: Determining the locations in Bangalore with the highest concentration of restaurants and listing the top 10.
Distribution of Restaurant Ratings: Analyzing the distribution of restaurant ratings in Bangalore.
Correlation between Votes and Ratings: Investigating correlations between the number of votes received by a restaurant and its rating.
Top 10 Rated Restaurants: Identifying the top 10 rated restaurants in Bangalore.
Online Ordering and Table Booking Services: Determining the number of restaurants offering online ordering and table booking services.
Likelihood of Online Ordering and Table Booking: Identifying which restaurant types are most likely to offer online ordering and table booking.
Rating Differences with Online Ordering: Analyzing the average ratings of restaurants with and without online ordering services.
Rating Distribution by Cost for Two People: Investigating the distribution of restaurant ratings based on the approximate cost for two people.
Rating Differences by Listing Type: Determining if there are differences in restaurant ratings based on the type of listing.
