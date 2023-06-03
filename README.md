# Hotel Booking Analysis EDA Project

This repository contains an Exploratory Data Analysis (EDA) project focused on hotel booking data. The project aims to analyze and gain insights from a dataset related to hotel bookings, exploring various aspects such as booking patterns, customer preferences, and trends.


Dataset:

The dataset used in this project consists of information about hotel bookings, including details about the bookings, guests, and hotel properties. The dataset contains various features such as:


Hotel: The name of the hotel (categorical)

IsCanceled: Whether the booking was canceled (binary: 1 if canceled, 0 if not)

LeadTime: Number of days between the booking and arrival date (numeric)

ArrivalDate: Date of arrival (date)

StaysInWeekendNights: Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel (numeric)

StaysInWeekNights: Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel (numeric)

Adults: Number of adults (numeric)

Children: Number of children (numeric)

Babies: Number of babies (numeric)

Meal: Type of meal booked (categorical)

Country: Country of origin (categorical)

MarketSegment: Market segment designation (categorical)

DistributionChannel: Booking distribution channel (categorical)

IsRepeatedGuest: Whether the booking was made by a repeated guest (binary: 1 if repeated, 0 if not)

PreviousCancellations: Number of previous booking cancellations made by the customer (numeric)

PreviousBookingsNotCanceled: Number of previous bookings not canceled by the customer (numeric)

ReservedRoomType: Code of the room type reserved (categorical)

AssignedRoomType: Code for the type of room assigned to the booking (categorical)

BookingChanges: Number of changes made to the booking before arrival (numeric)

DepositType: Type of deposit made by the customer (categorical)

Agent: ID of the travel agency or entity that made the booking (categorical)

Company: ID of the company/entity that made the booking or responsible for paying the booking (categorical)

DaysInWaitingList: Number of days the booking was in the waiting list before being confirmed (numeric)

CustomerType: Type of booking, assuming one of four categories (categorical)

ADR: Average daily rate as defined by dividing the sum of all transaction revenue by the total number of staying nights (numeric)

RequiredCarParkingSpaces: Number of car parking spaces required by the customer (numeric)

TotalOfSpecialRequests: Number of special requests made by the customer (numeric)

ReservationStatus: Reservation last status (categorical)

Project Goals:

The main objectives of this project are as follows:


Perform exploratory data analysis to gain insights into the hotel booking dataset.
Analyze booking patterns, such as booking lead time, booking changes, and booking cancellations.
Identify customer preferences in terms of meal type, room type, and special requests.
Explore the distribution of bookings across different countries and market segments.
Investigate the impact of various factors on booking cancellation rates.
Visualize trends and patterns in the dataset using appropriate charts and graphs.
Draw conclusions and provide recommendations based on the analysis.
Project Structure
The project repository is structured as follows:

data/: This directory contains the hotel booking dataset in CSV format.
notebooks/: This directory contains Jupyter notebooks with the EDA code
