# -UBER-RIDE-INSIGHTS-NAVIGATING-MOBILITY-DATA
The objective of this project is to utilize SQL queries and analysis to extract meaningful insights and answer various questions related to the ride-hailing business. We will explore trends, patterns, and relationships within the dataset to provide recommendations and solutions that can enhance the operational efficiency and customer experience of the ride-hailing service.

In our analysis of Uber's Ride-Hailing Operations, we delve into a dataset encompassing three core tables: 'Rides,' 'Drivers,' and 'Passengers'. The 'Rides' table encompasses detailed ride-related information such as ride specifics, driver and passenger identifiers,

pickup and dropoff locations, ride distance, duration, fare amount, and payment methods. The 'Drivers' table encapsulates essential driver attributes including driver ID, name, join date, rating, ride count, and earnings. Lastly, the 'Passengers' table encompasses passenger attributes, such as passenger ID, name, signup date, total rides taken, total spending, and passenger ratings. 
Description of  ‘Rides’ Table:

·       ride_id: Unique identifier for each ride.

·       driver_id: Identifier for the driver who conducted the ride.

·       passenger_id: Identifier for the passenger who took the ride.

·       pickup_location: Location where the ride started (pickup point).

·       dropoff_location: Location where the ride ended (dropoff point).

·       ride_distance: Distance covered during the ride (in kilometers or miles).

·       ride_duration: Duration of the ride in minutes.

·       ride_timestamp: Date and time when the ride took place.

·       fare_amount: Fare charged for the ride.

·       payment_method: Method used for payment (e.g., "Credit Card," "Cash").

 Description of  ‘Drivers’ Table:

·       driver_id: Unique identifier for each driver.

·       driver_name: Full name of the driver.

·       join_date: Date when the driver joined the service.

·       rating: Average rating of the driver based on passenger feedback.


·       total_rides: Total number of rides completed by the driver.

·       earnings: Total earnings of the driver.


Description of  ‘Passengers’ Table:

·       passenger_id: Unique identifier for each passenger.

·       passenger_name: Full name of the passenger.

·       signup_date: Date when the passenger signed up for the service.

·       total_rides: Total number of rides taken by the passenger.

·       total_spent: Total amount spent by the passenger on rides.

·       rating: Average rating given by drivers to the passenger.

 Questions:


Basic Level:

1.           What are & how many unique pickup locations are there in the dataset?

2.           What is the total number of rides in the dataset?

3.           Calculate the average ride duration.

4.           List the top 5 drivers based on their total earnings.

5.           Calculate the total number of rides for each payment method.

6.           Retrieve rides with a fare amount greater than 20.

7.           Identify the most common pickup location.

8.           Calculate the average fare amount.

9.           List the top 10 drivers with the highest average ratings.

10.      Calculate the total earnings for all drivers.

11.      How many rides were paid using the "Cash" payment method?

12.      Calculate the number of rides & average ride distance for rides originating from the 'Dhanbad' pickup location.

13.      Retrieve rides with a ride duration less than 10 minutes.

14.      List the passengers who have taken the most number of rides.

15.      Calculate the total number of rides for each driver in descending order.

16.      Identify the payment methods used by passengers who took rides from the 'Gandhinagar' pickup location.

17.      Calculate the average fare amount for rides with a ride distance greater than 10.

18.      List the drivers in descending order accordinh to their total number of rides.

19.      Calculate the percentage distribution of rides for each pickup location.

20.      Retrieve rides where both pickup and dropoff locations are the same.



Intermediate Level:     

                 

1.           List the passengers who have taken rides from at least 300 different pickup locations.

2.           Calculate the average fare amount for rides taken on weekdays.

3.           Identify the drivers who have taken rides with distances greater than 19.

4.           Calculate the total earnings for drivers who have completed more than 100 rides.

5.           Retrieve rides where the fare amount is less than the average fare amount.

6.           Calculate the average rating of drivers who have driven rides with both 'Credit Card' and 'Cash' payment methods.

7.           List the top 3 passengers with the highest total spending.

8.           Calculate the average fare amount for rides taken during different months of the year.

9.           Identify the most common pair of pickup and dropoff locations.

10.      Calculate the total earnings for each driver and order them by earnings in descending order.

11.      List the passengers who have taken rides on their signup date.

12.      Calculate the average earnings for each driver and order them by earnings in descending order.

13.      Retrieve rides with distances less than the average ride distance.

14.      List the drivers who have completed the least number of rides.

15.      Calculate the average fare amount for rides taken by passengers who have taken at least 20 rides.

16.      Identify the pickup location with the highest average fare amount.

17.      Calculate the average rating of drivers who completed at least 100 rides.

18.      List the passengers who have taken rides from at least 5 different pickup locations.

19.      Calculate the average fare amount for rides taken by passengers with ratings above 4.

20.      Retrieve rides with the shortest ride duration in each pickup location.



Advanced Level:

1.           List the drivers who have driven rides in all pickup locations.

2.           Calculate the average fare amount for rides taken by passengers who have spent more than 300 in total.


3.           List the bottom 5 drivers based on their average earnings.

4.           Calculate the sum fare amount for rides taken by passengers who have taken rides in different payment methods.

5.           Retrieve rides where the fare amount is significantly above the average fare amount.

6.           List the drivers who have completed rides on the same day they joined.

7.           Calculate the average fare amount for rides taken by passengers who have taken rides in different payment methods.

8.           Identify the pickup location with the highest percentage increase in average fare amount compared to the overall average fare.

9.           Retrieve rides where the dropoff location is the same as the pickup location.

10.           Calculate the average rating of drivers who have driven rides with varying pickup locations.
