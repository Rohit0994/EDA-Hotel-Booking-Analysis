# EDA-Hotel-Data-Analysis
# Objective 
We are provided with a hotel bookings dataset.

Our main objective is perform EDA on the given dataset and draw useful conclusions about general trends in hotel bookings and how factors governing hotel bookings interact with each other.

# Dataset
We are given a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. It contains the following features.


1. **hotel** : Hotel (Resort Hotel or City Hotel)
2. **is_canceled** : Value indicating if the booking was canceled (1) or not (0)
3. **lead_time** : Number of days that elapsed between the entering date of the booking into the PMS and the arrival date
4. **arrival_date_year** : Year of arrival date
5. **arrival_date_month** : Month of arrival date
6. **arrival_date_week_number** : Week number of year for arrival date
7. **arrival_date_day_of_month** : Day of arrival date
8. **stays_in_weekend_nights** : Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
9. **stays_in_week_nights** : Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
10. **adults** : Number of adults
11. **children** : Number of children
12. **babies** : Number of babies
13. **meal** : Type of meal booked. Categories are presented in standard hospitality meal packages:
14. **country** : Country of origin.`
15. **market_segment** : Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”
16. **distribution_channel** : Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”
17. **is_repeated_guest** : Value indicating if the booking name was from a repeated guest (1) or not (0)
18. **previous_cancellations** : Number of previous bookings that were cancelled by the customer prior to the current booking
19. **previous_bookings_not_canceled** : Number of previous bookings not cancelled by the customer prior to the current booking
20. **reserved_room_type** : Code of room type reserved. Code is presented instead of designation for anonymity reasons.
21. **assigned_room_type** : Code for the type of room assigned to the booking.
22. **booking_changes** : Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation
**deposit_type** : Indication on if the customer made a deposit to guarantee the booking.
23. **agent** : ID of the travel agency that made the booking
24. **company** : ID of the company/entity that made the booking or responsible for paying the booking.
25. **days_in_waiting_list** : Number of days the booking was in the waiting list before it was confirmed to the customer
26. **customer_type** : Type of booking, assuming one of four categories
27. **adr** : Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights
28. **required_car_parking_spaces** : Number of car parking spaces required by the customer
29. **total_of_special_requests** : Number of special requests made by the customer (e.g. twin bed or high floor)
30. **reservation_status** : Reservation last status, assuming one of three categories
a). **Canceled** – booking was canceled by the customer
b). **Check-Out** – customer has checked in but already departed
c). **No-Show** – customer did not check-in and did inform the hotel of the reason 
31. **reservation_status_date** : Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel
Total number of rows in data: 119390
Total number of columns: 32

# Know your data
1. Dataset Information
2. Duplicate Values
3. Missing Values/Null Values
4. Understanding Your Variables
5. Check Unique Values for each variable.

# Data wrangling
1.count that in which year of which month most number of customers arrived at  hotel.
2.Customer type, Room type, room_comparision, Deposit_type, Is_canceled checked.
3.How many customer have changed their booking.
4.remove duplicates values
5.finding uniques values for each variables
6.Find hotel ratio
7.Adding a  two new column of total staying days,total people stays
8.Remove outliers by box plot.
Did All th manipulation


# What main questions was arising :-
1. Which types of customers mostly make bookings?
2. Which room type is in most demand and which room type generatesthe  highest adr?
3. Which distribution channel brings betterrevenue-generatingg deals for hotels?
4. Which significant distribution channel has the highest cancellation percentage?
5. What is the trend of bookings within a month?
6. Which Hotel has Highest booking ratio(comparision)?
7. What is preferred stay length in hotel if we compare with Customer type?
8. In which year most booking has happened for bothe type hotels?
9. From which country most of the guests are coming ?
10. In which month most of the booking happened?
11. Which market segment has booked and canceled the booking?
12. What type of Customer has highest booking as Couples, Single, Group?
13. Which meal type is the most preffered meal of customers?
14. Finding out corelation between Different variables?
15. which has highet ADR?

 


# Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:

1. Bar Plot
2. Histogram
3. Scatter Plot
4. Pie Chart
5. Line Plot
6. Heatmap
7. Box Plot
8. Pair plot

# We plot different graph (univariate and bivariate ) to make find out the last conclusion:-

1. Around 60% bookings are for City hotel and 40% bookings are for Resort hotel, therefore City Hotel is busier than Resort hotel. Also the overall adr of City hotel is slightly higher than Resort hotel.
2. Mostly guests stay for less than 5 days in hotel and for longer stays Resort hotel is preferred.
3. Both hotels have significantly higher booking cancellation rates and very few guests less than 3 % return for another booking in City hotel. 5% guests return for stay in Resort hotel.
4. Most of the guests came from european countries, with most of guests coming from Portugal.
5. Guests use different channels for making bookings out of which most preferred way is TA/TO.
6. Almost 30% of bookings via TA/TO are cancelled.
7. July- August are the most busier and profitable months for both of hotels.
8. Couples are the most common guests for hotels, hence hotels can plan services according to couples needs to increase revenue.
9. For customers, generally the longer stays (more than 15 days) can result in better deals in terms of low adr.
10. Higher lead time has higher chance of cancellation. Also, history of previous cancellations increases chances of cancellation.



# Challenges
1. There was a lot of duplicate data.
2. Data was present in wrong datatype format.
3. Choosing appropriate visualization techniques to use was difficult.
4. A lot of null values were there in the dataset.
