

✈️ Airline Price & Operations Analytics Project
📌 Project Title
Airline KPI Dashboard & Pricing Analysis Using Python

📖 Project Description
This project focuses on analyzing airline flight data to uncover key insights related to ticket pricing, airline competition, flight convenience, refund policies, and value-for-money metrics.
Using Python and pandas, the dataset was cleaned, preprocessed, feature-engineered, and transformed into business-driven KPIs.
 A single-screen KPI dashboard was created using matplotlib to visually represent airline market behavior.
The project demonstrates end-to-end data analytics skills, from raw data cleaning to insight-driven decision-making.

📊 Data Description
The dataset contains flight-level information with the following key attributes:
airline – name of the airline


source_city – departure city


destination_city – arrival city


departure_time – time of departure (morning, afternoon, night, etc.)


arrival_time – time of arrival


stops – number of stops (non-stop, one-stop, etc.)


class – travel class (economy / business)


duration – total flight duration (hours)


days_left – days left until departure


price – ticket price


🧹 Data Preprocessing Performed
Removed duplicate records


Handled missing values:


median for price


mode for categorical columns (stops)


Fixed column naming issues (lowercase & stripped)


Created new engineered features:


refundable


pre_booked_meal



📈 KPI Questions (Business Metrics)
The following Key Performance Indicators (KPIs) were designed to answer real business questions:
What is the average ticket price in the market?


What is the minimum and maximum ticket price available?


How does pricing vary by airline?


Which airlines have the highest market share?


What is the ratio of non-stop vs connecting flights?


What is the average flight duration?


How do stops impact flight duration?


How does departure time affect pricing?


What is the cost per hour of travel (value-for-money)?


How do refundability and meals affect ticket pricing?


How does booking window (days_left) influence price?



⚙️ Project Process
Step 1: Data Cleaning
Checked and removed duplicate rows


Handled missing values


Validated clean dataset (0 nulls, 0 duplicates)


Step 2: Feature Engineering
Refundable Logic


Ticket is refundable if days_left > 3


Pre-booked Meal Logic


Meal included for night & afternoon flights


Step 3: KPI Computation
Aggregations using groupby, mean, value_counts


Pricing, duration, and value metrics calculated


Step 4: Visualization
Built two non-scrollable KPI dashboards


Used matplotlib subplots


Business-focused layout with clear labeling



📊 Dashboard Overview
The dashboards include:
Dashboard 1 – Market & Pricing
Average ticket price by airline


Number of flights per airline


Ticket price distribution


Non-stop vs one-stop ratio


Duration vs price analysis


Cost per hour of travel


Dashboard 2 – Policy & Behavior
Price by class


Price by stops


Refundable vs non-refundable tickets


Pre-booked meal vs pricing


Booking window vs price behavior


📌 All charts are displayed in a single screen (non-scrollable) for executive-level readability.

🔍 Key Project Insights
Business class flights are significantly more expensive but offer better value-per-hour


Non-stop flights dominate customer preference due to time efficiency


Tickets booked earlier (higher days_left) tend to be cheaper and refundable


Night and afternoon flights commonly include pre-booked meals


Certain airlines consistently provide better value-for-money


Stops increase duration disproportionately compared to price savings



✅ Conclusion
This project successfully demonstrates how raw airline data can be transformed into actionable business insights using Python.
It showcases:
Strong data cleaning & preprocessing skills


KPI-driven analytical thinking


Business-oriented feature engineering


Professional dashboard creation


The analysis can support:
Pricing strategy decisions


Airline competitiveness studies


Customer value and convenience evaluation



🛠️ Tools & Technologies Used
Python


Pandas


NumPy


Matplotlib


Jupyter Notebook



🚀 Future Enhancements
Predictive modeling for ticket price forecasting


Interactive dashboard using Streamlit


Route-wise and seasonal trend analysis


Integration with Power BI / Tableau



👤 Author
Zeeshan Hussain



