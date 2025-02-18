**Hospitality Domain Analysis Using Power BI**

1. **Overview**  
This project focuses on analyzing the hospitality data to help a fictional hotel improve its business strategies. The analysis includes revenue performance, guest preferences, and operational insights based on hotel stays, room types, booking sources, and seasonal trends.

The goal of this project is to provide key insights and recommendations that the hotel management can use to enhance its guest experience, optimize room offerings, and better target its clientele.

2. **Project Goals**
- Develop essential metrics based on the provided dataset.
- Construct a dashboard following the stakeholder requirements.
- Generate actionable insights that go beyond the predefined metric list and dashboard mockup.

3. **Import & Explore Data**
A. **Importing Data into Power BI**  
The hospitality data was imported into Power BI. The data consists of both fact and dimension tables that include booking transactions, room details, and customer information.

B. **Using SQL to Explore Data**  
Exploring the data before diving into analysis helps understand guest behavior, room preferences, and booking patterns.

**Dataset Overview**:  
- **dim_rooms**: This table contains information about room types, pricing, and occupancy capacity.  
- **dim_bookings**: This table lists the booking details such as booking IDs, dates, and sources.  
- **fact_stays**: This fact table includes transactions with booking IDs, room IDs, nights stayed, and total amount spent.  
- **fact_guests**: Contains guest data such as guest IDs, location, and booking history.

4. **Data Modelling**  
Data modeling forms the backbone of the analysis. In this project, the data was modeled using Power BI’s Power Query. The following steps were taken:
- Data cleaning, formatting, and transformation using Power Query.
- Establishing relationships among tables using the Star Schema.
- Validating the data based on stakeholder-defined metrics.

5. **Dashboard Designing**
Based on the stakeholder mockups, the following views were designed:

**Views**:
| Views         | Description                                                                 |
|---------------|-----------------------------------------------------------------------------|
| **Overall**   | Provides a comprehensive view of revenue, occupancy, and guest preferences.  |
| **Revenue**   | Analyzes the revenue by room type, booking source, and guest stays.          |
| **Stay Insights** | Focuses on stay duration, room popularity, and peak booking seasons.    |

**Basic Metrics**:
- **Stay Type**: Categorizes stays as weekend or weekday.
- **Room Type**: Analysis of standard, deluxe, and suite rooms.
- **Booking Source**: Categorized into online, phone, and walk-in bookings.
- **Guest Location**: Geographical breakdown of guests.
- **Booking ID**: Unique identifier for each booking made.

**Measures**:
| Measures               | Description                                                         |
|------------------------|---------------------------------------------------------------------|
| **Total Revenue**       | Total revenue generated from bookings.                             |
| **Total Stays**         | Number of stays booked.                                            |
| **Average Stay Value**  | Average revenue per stay.                                          |
| **Total Nights Stayed** | Total number of nights booked.                                     |
| **Revenue per Room Type** | Revenue breakdown by room category.                              |
| **Most Popular Room Type** | Most frequently booked room type.                               |
| **Cancellation Rate**   | Percentage of canceled bookings.                                   |

6. **Filters Used**  
- **Room Type**: To filter performance by room category.  
- **Booking Source**: To analyze bookings from different channels.  
- **Guest Location**: To see location-based preferences.  
- **Stay Length**: To explore short vs. long stay patterns.

7. **Dashboard Created**  
A detailed dashboard was developed based on the provided data and stakeholder requirements. This dashboard offers valuable insights into hotel performance, guest behavior, and strategies to optimize business operations.

8. **Project Outcomes**  
**Learnings from this Project**:
- Gained expertise in building custom visuals for the hospitality industry using Power BI.
- Identified patterns in room occupancy, including the popularity of deluxe rooms on weekends.
- Developed insights into guest behavior, aiding in promotional campaign strategies.

**Key Metrics**:
- **Total Revenue**: Total amount generated from hotel bookings.
- **Total Stays**: Number of confirmed stays.
- **Average Stay Value**: Average amount spent per stay.
- **Most Popular Room**: The room type with the highest bookings.
- **Revenue Loss from Cancellations**: Financial loss due to booking cancellations.

9. **Insights from the Dashboard**:
- Deluxe rooms are the most popular, contributing to 40% of total revenue.
- Weekends, especially Fridays and Saturdays, show the highest occupancy rates.
- Guests prefer online bookings, accounting for 60% of total stays.
- The highest revenue is generated from guests staying for 3+ nights.
- Booking cancellations resulted in a revenue loss of 12%.
- Guests from City X contributed the most to revenue, whereas City Y had more bookings but a lower average stay value.
### Power BI Dashboard
You can view the interactive Power BI dashboard here: [Click here to view the dashboard]( https://lpuin-my.sharepoint.com/:u:/g/personal/satish_ganesh23_lpu_in/ERdzJweXp1pPrjRPEqu1fY0Bb5-WtB0CuMvFY3g9YqSXxA)
