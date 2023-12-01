DATA SCIENCE FALL '23 - FOODHUB DATA ANALYSIS

CONTEXT: New York is known for its diverse fascinating restaurants, and those who are aware, the number of restaurants is increasing day by day. Due to hectic lifestyles, majority of the customers are students and professionals. Online food delivery service has become crucial and convenient. FoodHub offers access to multiple restaurants through their app.

The app allows the restaurants to receive a direct online order from a customer. Unlike other food apps, it assigns a delivery person from the company to pick up the order after it is confirmed by the restaurant. The delivery person then uses the map to reach the restaurant and waits for the food package. Once the food package is handed over to the delivery person, he/she confirms the pick-up in the app and travels to the customer's location to deliver the food. The delivery person confirms the drop-off in the app after delivering the food package to the customer. The customer is allowed to rate the order in the app. The company's revenue comes from collecting a fixed margin of the delivery order from the restaurants.

OBJECTIVE: The food aggregator company has stored the data of the different orders made by the registered customers in their online portal. An exploratory data analysis will be done to get have osme idea idea about the demand of different restaurants which will help them in enhancing their customer experience.

DATA DESCRIPTION: The data contains the different data related to a food order.

DATA DICTIONARY:

order_id: Unique ID of the order

customer_id: ID of the customer who ordered the food

restaurant_name: Name of the restaurant

cuisine_type: Cuisine ordered by the customer

cost: Cost of the order
day_of_the_week: Indicates whether the order is placed on a weekday or weekend
rating: Rating given by the customer out of 5
food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information
