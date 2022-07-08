# NYC-taxi-trip-time-prediction

Data and Problem Statement:

The data used in this study are all subsets of New York City Taxi, which contains observations on around 1.4 million+ of New York City taxi rides in the year 2016. To build the models, 1 million observations were used, of which 800,000+ were used for training and 200,000+ for validation. 
The main objective is to build a predictive model, which could help in predicting the duration time of the ride. This would in turn help them in matching the right cabs with the right customers quickly and efficiently. 

⦁	id - a unique identifier for each trip
⦁	vendor_id - a code indicating the provider associated with the trip record
⦁	pickup_datetime - date and time when the meter was engaged
⦁	dropoff_datetime - date and time when the meter was disengaged
⦁	passenger_count - the number of passengers in the vehicle (driver entered value)
⦁	pickup_longitude - the longitude where the meter was engaged
⦁	pickup_latitude - the latitude where the meter was engaged
⦁	dropoff_longitude - the longitude where the meter was disengaged
⦁	dropoff_latitude - the latitude where the meter was disengaged
⦁	pickup_day - Day of the week
⦁	dropoff_day - Day of the week
⦁	pickup_day_no - Day of the week in numerical representation
⦁	dropoff_day_no - Day of the week in numerical representation
⦁	pickup_hours – The hour of the pickup time(24 hour format)
⦁	dropoff_hours– The hour of the pickup time(24 hour format)
⦁	pickup_month – Pick up month in numerical representation
⦁	dropoff_month - Pick up month in numerical representation
⦁	pickup_shift - Shift of the day
⦁	dropoff_shift - Shift of the day
⦁	store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip
⦁	trip_duration - duration of the trip in seconds
⦁	distance – The distance between the ride in KM.
