# Taxi Fare Analysis and Prediction
- In this project we will be predicting taxi fare price for trip undertook by the passengers.
- The data is collected from Kaggle 
- These are general information about the dataset:
- Dataset :
  
⏱️ 'trip_duration': How long did the journey last?[in Seconds]

🛣️ 'distance_traveled': How far did the taxi travel?[in Km]

🧑‍🤝‍🧑 'num_of_passengers': How many passengers were in the taxi?

💵 'fare': What's the base fare for the journey?[In INR]

💲 'tip': How much did the driver receive in tips?[In INR]

🎀 'miscellaneous_fees': Were there any additional charges during the trip?e.g. tolls, convenience fees, GST
etc.[In INR]

💰 'total_fare': The grand total for the ride (this is your prediction target!).[In INR]

⚡ 'surge_applied': Was there a surge pricing applied? Yes or no?


### For preprocessing cleaning, we have generate these insights:
  1. In num_of_passengers, 0 and above above 6 values are doubtful.
  2. In distance_traveled, rows with above 110 km values are doubtful. As it is not possible to travel that much in a city at once.
  3. In fare and total_fare, rows with Rs. 0 values should be eliminated.
  4. In miscellaneous_fees, values which are negative should be eliminated.
  5. In trip_duration, any passenger would take taxi for atleast 1 mins below it doesn't make sense.

# Models and Score
- Linear Regression has given score of 0.8001099072483999
- Random Forest has given score of 0.8252940295029709
  
  - 
