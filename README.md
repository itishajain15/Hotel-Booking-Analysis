# Hotel-Booking-Analysis
Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions! This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data. Explore and analyze the data to discover important factors that govern the bookings.

Features Hotel - Hotel (H1 = Resort Hotel or H2 = City Hotel)

Is_canceled - Value indicating if the booking was canceled (1) or not (0).

Lead_time- Number of days that elapsed between the entering date of the booking into the PMS and the arrival date

Arrival_date_year - Year of arrival date

Arrival_date_month - Month of arrival date

Arrival_date_week_number - Week number of year for arrival date

Arrival_date_day_of_month - Day of arrival date

Stays_in_weekend_nights - Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel

Stays_in_week_nights -Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel

Adults - Number of adults

Children - Number of children

Babies - Number of babies

Meal - Type of meal booked. Categories are presented in standard hospitality meal packages: Undefined/SC – no meal package; BB – Bed & Breakfast; HB – Half board (breakfast and one other meal – usually dinner) FB – Full board (breakfast, lunch and dinner)

Country-Country of origin. Categories are represented in the ISO 3155–3:2013 format

Market_segment - Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”

Distribution_channel - Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”

Is_repeated_guest - Value indicating if the booking name was from a repeated guest (1) or not (0)

Previous_cancellations - Number of previous bookings that were canceled by the customer prior to the current booking

Previous_bookings_not_canceled - Number of previous bookings not canceled by the customer prior to the current booking

Reserved_room_type - Code of room type reserved. Code is presented instead of designation for anonymity reasons

Assigned_room_type - Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation reasons (e.g. overbooking) or by customer request. Code is presented instead of designation for anonymity reasons

Booking_changes - Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation

Deposit_type-Indication on whether the customer made a deposit to guarantee the booking. This variable can assume three categories: No Deposit – no deposit was made; Non Refund – a deposit was made in the value of the total stay cost; Refundable – a deposit was made with a value under the total cost of stay.

Agent - ID of the travel agency that made the booking

Company - ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons

Days_in_waiting_list - Number of days the booking was in the waiting list before it was confirmed to the customer

Customer_type - Type of booking, assuming one of four categories: Contract - when the booking has an allotment or other type of contract associated to it; Group – when the booking is associated to a group; Transient – when the booking is not part of a group or contract, and is not associated with other transient booking; Transient-party – when the booking is transient, but is associated to at least other transient booking

Adr - Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights

Required_car_parking_spaces - Number of car parking spaces required by the customer

Total_of_special_requests - Number of special requests made by the customer (e.g. twin bed or high floor)

Reservation_status - Reservation last status, assuming one of three categories: Canceled – booking was canceled by the customer; Check-Out – customer has checked in but already departed; No-Show – customer did not check-in and did inform the hotel of the reason why

Reservation_status_date - Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when the booking was canceled or when the customer checked-out of the hotel.

The dataset we have contains 119390 rows and 32 columns. This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, customers who canceled their reservations and who did not cancel, length of stay, the number of adults, types of rooms, children, and/or babies, and the number of available parking spaces, among other things.
