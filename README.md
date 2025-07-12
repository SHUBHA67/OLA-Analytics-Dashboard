# Ola Cab Service Insights Dashboard

An interactive Power BI dashboard built to analyze operational efficiency, customer behavior, and financial metrics of Ola rides—highlighting trends in bookings, cancellations, driver performance, and ride demand across cities.

# Project/Dashoboard Description : 
The Ola Cab Service Insights Dashboard is a comprehensive visualization tool designed to help stakeholders monitor and analyze booking trends, cancellations, revenue, and ride efficiency across various vehicle types. It enables data-driven decisions in ride optimization, customer experience, and better operational planning.

# Tech Stack : 
The dashboard was built using the following tools and technologies:
• 📊 Power BI Desktop – For data visualization and dashboard development.
• 🧮 DAX (Data Analysis Expressions) – To create dynamic KPIs and measures.
• 🔁 Power Query (M Language) – For cleaning and transforming raw data into useful data.
• 💾 SQL – Used for complex querying and data aggregation before importing into Power BI.
• 📁 File Format – .pbix for development and .png for dashboard snapshots.

# Data Source
Source: Ola ride and booking database (internal mock dataset)
The dataset consists of structured records capturing ride bookings, ride status, driver ratings, payment modes, vehicle types, and cancellation reasons. Supplemented with regional and customer information for detailed insights.

# Features / Highlights :
**• Business Problem :**
Ola faces challenges in monitoring ride completion rates, customer satisfaction, and operational inefficiencies due to manual data exploration. Key questions around cancellations, driver performance, revenue, and geographic demand remain hard to analyze through raw data.
  
**• Goal of the Dashboard :**
To build a self-service BI dashboard that:
  A) Visualizes ride bookings and cancellation patterns
  
  B) Tracks performance across vehicle types and cities
  
  C) Highlights customer and driver behavior trends
  
  D) Enables stakeholder decisions in marketing, operations, and customer care
  
  • Walkthrough of Key Visuals
  1. KPIs (Top Panel)
  
  [1] Total Bookings
  
  [2] Completed Rides
  
  [3] Cancelled Rides
  
  [4] Revenue Generated
  
  [5] Avg. Customer Rating
  
**2. Ride Status Breakdown (Pie-Chart):**  
Visualizes the proportion of successful vs. cancelled vs. pending rides.
  
**3. Booking Trends Over Time (Line Graph):** 
Shows booking volume across time with date slicers for dynamic range.

**4. Vehicle Type Insights (Bar/Column Visuals):**
Compares ride volume, revenue, and ratings across vehicle types (Mini, Prime, Sedan, Auto, etc.)
  
**5. Cancellation Analysis (Pie-Chart + Filter):** 
Cancellation reasons split by rides cancelled by drivers and customers with category filters and date sclicers.
  
**6. Payment Method Distribution (Column Chart):**
Displays breakdown of UPI, card, cash, and wallet-based payments.

# Business Impact & Insights:

A)Highlights a major opportunity to reduce cancellations and improve operational efficiency.

B)Cash is the dominant payment method, followed by UPI. The business can reduce operational overhead by incentivizing digital payments (UPI) with discounts or loyalty points.

C)Despite high booking values, Mini and Prime Plus have slightly lower success rates than E-Bikes—perhaps due to availability or driver issues. 

D)Customer cancellations are led by “Change of Plans” and “Driver is not moving.” Driver cancellations are primarily due to personal/car issues and customer being unresponsive. Improves understanding of cancellation friction points.

E)Ratings for both drivers and customers are consistently around 4.00, but Bike and Mini vehicles slightly underperform. Indicates that experience is generally consistent, but Bike ride comfort and driver behavior might need improvement.

# Some Dashboard Snapshots : 
https://github.com/SHUBHA67/OLA-Analytics-Dashboard/blob/main/Screenshot%20of%20Dashboard%20-%20Cancellations.PNG
https://github.com/SHUBHA67/OLA-Analytics-Dashboard/blob/main/Screenshot%20of%20Dashboard%20-%20Revenue.PNG



