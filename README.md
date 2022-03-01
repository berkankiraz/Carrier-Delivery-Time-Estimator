# Carrier-Delivery-Time-Estimator
⚫ For food delivery companies, the timing of the courier plays a very vital role. For this
purpose, a model will be created to estimate the estimated time taken for a delivery. In
the given dataset,
"New_Last_Restaurant_Preparation_Time","New_Departure_Time","New_Courier_
Transport_Time","Uctanuomer_Delivery_Time","Customer",Customer
"CustomerLon","RestaurantLat","RestaurantLon" data will be used for time
estimation calculation.

⚫ The goal of the project is to estimate the total duration between
"CRMe_delivery_time" and "actual_delivery_time", also known as total delivery
time.

⚫ Several columns from the dataset contain some missing values, after digging out the
data. It is decided to use mean value approache to either fill up or drop the missing
values for each column. 

⚫ A function was created to calculate the distanceusing "CustomerLat", "CustomerLon",
"RestaurantLat", "RestaurantLon"
