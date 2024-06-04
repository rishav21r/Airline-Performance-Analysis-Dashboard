# Enhancing Airline Performance Analysis for the Department of Transport
This repository contains a project for analyzing and visualizing flight delays in the US for the year 2015. The project includes data on flight delays, cancellations, and various factors affecting airline performance.

## Project Background
the Department of Transport has hired you and your consultancy team to present key performance indicators (KPIs) from airline performance data. The Department tracks the on-time performance of domestic flights operated by large air carriers. Despite having access to a vast array of data, the Department's management has had difficulty interpreting which data is critical for ongoing and future success.

## Objectives
- Identify 5 – 7 Key Performance Indicators (KPIs) for the Department of Transport.
- Create a single dashboard of information for management review.
- Visually display the KPIs and justify each KPI’s selection and design.
- Present trends, analysis, and patterns.

## Data
The data used in this project includes:
- `airports.csv`: Information about the airports.
- `airlines.csv`: Information about the airlines.
- `flights.csv`: Detailed flight data (not included due to size).

## Tableau Dashboard
The dashboard created for this project provides a comprehensive overview of flight delays, cancellations, and their reasons. Below is a screenshot of the dashboard:

![alt text][logo]

[logo]: dashboard/flightsdelaydashboard.png "Flights Delay Dashboard"

## Key Performance Indicators (KPIs) and presumed Root Cause Analysis
Recognising that not all data points are equally significant, we have meticulously identified and evaluated KPIs that capture the essence of airline performance. These KPIs are carefully chosen to align with the Department's objectives, offering a holistic perspective on on-time performance, delays, and cancellations.

### 1. Number of delayed flights by departure region
It is important for an airline company to understand what regions have the highest frequency of delayed flights. These regions can be broken up into individual states and the airports located within them. This data provides airlines with a broad identification of the regions in which they can improve. Reducing the frequency of delays will help to reduce costs and boost customer satisfaction.

### 2. Main reasons for cancellation
Another KPI for airline companies to consider is the most common causes of flight cancellation. Flight cancellations have a significant cost effect on airlines including compensation, accommodation and rebooking fees. Cancelled flights, more so than delays, can damage the reputation of an airline as customers value reliability from their provider. Understanding the main causes of cancellations can educate employees to address these problems or develop systems to streamline procedures and reduce cancellations.

### 3. Understand delay trends throughout the year
The third KPI identified is to understand how the trend of delays changes throughout the year. This information should show how the number of delays, and the reasons for the delay change throughout the year. It should also demonstrate the cumulative effect of these delays in regard to time. This can allow airline companies to identify periods throughout the year where delays are most common. Reducing the number of flight delays during these periods when delays are common can allow them to achieve their organisational objectives by improving their operational efficiency.

### 4. Cancelled flights by airline
By utilising the flight cancellations a better understanding of how operational efficiency can be increased as it showcases the airline's operational inefficiencies, such inefficiencies might be relevant to either physical features on the plane malfunctioning or technical systems requiring updates. Using the frequency of cancellations by the airline, suggestions can be made for potential resource allocations to the desired areas, thus an airline that is engulfed with cancellations may benefit from a risk management strategy.  
From the dashboard constructed the cancelled flights by airlines section highlights the largest quantity of flights cancelled was from Southwest Airlines followed by Atlantic Southeast Airlines. The data also presents the top three reasons why flights were cancelled with the largest number of flights being cancelled due to weather conditions. The map on the dashboard also highlights the regions for which the weather conditions were at their highest.

### 5. Reasons for Cancelled Flights by Airports 
The fifth major key performance indicator (KPI) that emerged from the dashboard highlighted the major reasons for flight cancellations based on different airports. The results as shown in the dashboard revealed that bad weather was the major reason for cancellation across all airports, including Chicago O'Hare International, Dallas/Fort Worth International, Newark Liberty International, etc. The second major reason for cancellation across all airports was Airline/Carrier services, while the national air system was the third major reason for cancellations across all airports.  
 
### 6. Reasons for Delays

We have confirmed through the dashboard that flight delays are predominantly attributed to issues with the aircraft, followed by factors within the control of the airline, and subsequently, challenges within the air traffic management system. Furthermore, adverse weather conditions have emerged as a significant contributor to overall delays.
Late aircraft delays and airline delays may result from various factors, such as the late arrival of the incoming aircraft scheduled for the flight. Delays stemming from the aircraft's preceding flights can trigger a domino effect, causing subsequent flights to be delayed. Other challenges contributing to these delays include maintenance issues and crew scheduling difficulties.
Additionally, we observe that delays are influenced by air system issues, which may arise due to congestion or restrictions in airspace managed by Air Traffic Control (ATC). External factors like adverse weather conditions also play a notable role in contributing to delays.



