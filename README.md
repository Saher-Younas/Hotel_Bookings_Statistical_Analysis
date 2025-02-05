# Hotel Bookings Statistical Analysis Using Python

## Project Overview
This project analyzes hotel booking data to uncover patterns, trends, and key factors influencing customer behavior. The analysis aims to provide valuable insights for optimizing hotel operations and enhancing customer satisfaction.

## Objectives
- Perform **data cleaning** to ensure accuracy.
- Conduct **exploratory data analysis (EDA)** to identify trends.
- Use **statistical methods** to test hypotheses and validate findings.
- Provide **business recommendations** based on insights derived from the analysis.

## Dataset Details
The dataset consists of hotel booking records, including reservation details, customer demographics, and stay information.

### Key Features:
- **Hotel Type**: City Hotel or Resort Hotel.
- **Lead Time**: Time between booking and arrival.
- **Previous Cancellations**: Number of past cancellations.
- **Booking Changes**: Modifications made to the booking.
- **Special Requests**: Additional customer requests.
- **Customer Type**: Categories of customer segments.
- **Market Segment**: Channel through which the booking was made.
- **Stay Duration**: Length of stay at the hotel.
- **Meal Preference**: Type of meal plan selected.
- **ADR (Average Daily Rate)**: The revenue per available room.
- **Total Guests**: Number of adults, children, and babies.
- **Is Canceled**: Whether a booking was canceled or not.

## Data Cleaning & Preprocessing
To ensure the reliability of our analysis, data cleaning was performed, including:
- **Handling Missing Values**: Missing values in numerical and categorical features were analyzed and imputed appropriately.
- **Outlier Detection**: Boxplots and histograms were used to detect anomalies in booking lead times, stay durations, and ADR.
- **Data Type Adjustments**: Converted categorical variables into numerical format where needed.
- **Feature Engineering**: Created new features such as total guests, stay duration, and booking month for deeper analysis.

## Exploratory Data Analysis (EDA)
### 1. Booking Trends Over Time
- A **time-series analysis** revealed seasonal peaks in bookings, with **summer months** showing the highest demand.
- Resort hotels had more bookings during holidays, while city hotels showed stable demand throughout the year.

### 2. Cancellation Analysis
- **Cancellation rates** were significantly higher in city hotels compared to resort hotels.
- Customers with longer **lead times** were more likely to cancel their bookings.
- High ADR bookings had **higher cancellation rates**, indicating a possible relationship between pricing and cancellations.

### 3. Customer Demographics
- Most customers were from European countries, with **Portugal and the UK** being top sources of guests.
- Families and couples formed the majority of hotel guests.

### 4. Effect of Lead Time on Booking Behavior
- Shorter lead times correlated with lower cancellation rates.
- Bookings made **more than 90 days in advance** had the highest likelihood of cancellation.

### 5. Impact of Market Segments
- **Online Travel Agencies (OTAs)** contributed to the majority of bookings but had the highest cancellation rates.
- **Direct bookings** had the lowest cancellation rates, suggesting that encouraging direct bookings could improve revenue stability.

### 6. Average Daily Rate (ADR) Analysis
- The ADR for **city hotels** was higher compared to resort hotels.
- Seasonal pricing fluctuations were observed, with rates increasing during peak holiday seasons.

### 7. Special Requests & Customer Behavior
- Guests with multiple special requests had a **lower cancellation rate**.
- Customers making bookings with **meal plans included** were less likely to cancel.

## Statistical Hypothesis Testing
To validate findings, several hypotheses were tested:
1. **Do city hotels have higher cancellation rates than resort hotels?**
   - A chi-square test confirmed that city hotels have significantly higher cancellation rates.

2. **Does lead time affect cancellation probability?**
   - A t-test showed that longer lead times correlate with a higher likelihood of cancellation.

3. **Do direct bookings have lower cancellation rates than OTA bookings?**
   - A chi-square test validated that OTA bookings experience significantly higher cancellations.

4. **Does a higher ADR lead to more cancellations?**
   - A regression analysis indicated a positive correlation between ADR and cancellation rates.

5. **Do customers with special requests cancel less?**
   - A chi-square test confirmed that guests with special requests were less likely to cancel.

## Business Insights & Recommendations
- **Reduce Lead Times**: Implement dynamic pricing to encourage last-minute bookings, reducing cancellation risk.
- **Promote Direct Bookings**: Offer incentives for direct bookings to lower OTA-related cancellations.
- **Flexible Pricing Strategies**: Adjust ADR based on seasonality and booking trends to optimize revenue.
- **Improve Customer Retention**: Enhance services for long-term and repeat customers to build brand loyalty.
- **Monitor Cancellation Patterns**: Identify customer segments with high cancellations and introduce penalties or policies to mitigate losses.

## Tech Stack Used
- **Python** (Pandas, NumPy, Scipy, Matplotlib, Seaborn, Statsmodels)
- **Jupyter Notebook**



## Conclusion
This project provides a comprehensive statistical analysis of hotel bookings, offering valuable insights into **customer behavior, booking trends, and cancellation patterns**. The findings can help hotels optimize pricing strategies, reduce cancellations, and enhance customer retention.




