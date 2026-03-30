**🚆 UK Train Rides Data Analysis**


**📌 Project Overview**

This project focuses on analyzing railway journey data to understand passenger behavior, ticket pricing, and operational performance.

The analysis is performed using Python with powerful data analysis and visualization libraries.

The dataset includes information such as ticket class, payment method, journey status, delay reasons, and pricing. 

The main goal is to extract meaningful insights that can support better decision-making in transportation systems. 

This project demonstrates real-world application of data analytics techniques.


**🎯 Objectives**

Analyze passenger booking behavior and preferences

Study ticket pricing patterns across different categories

Identify delay patterns and operational efficiency

Explore time-based trends in ticket purchases and revenue

Perform univariate, bivariate, and multivariate analysis

Create attractive and informative visualizations


**📊 Dataset Information**

Source: https://mavenanalytics.io/data-playground/uk-train-rides

The dataset contains detailed information about train journeys in the UK

Includes both categorical and numerical features

Key columns include:

Transaction_ID

Ticket_Class

Ticket_Type

Ticket_Price

Payment_Method

Purchase_Type

Departure_Station

Journey_Status

Reason_for_Delay

Date_of_Journey

Time_of_Purchase


**🛠️ Tools & Technologies Used**

Python

Pandas – Data manipulation and analysis

NumPy – Numerical operations

Matplotlib – Basic visualizations

Seaborn – Advanced and attractive visualizations

Plotly – Interactive charts

Jupyter Notebook – Development environment


**🔧 Data Cleaning & Preprocessing**

Renamed columns for consistency and readability

Converted date and time columns into datetime format

Handled missing values using appropriate methods

Created new features such as:

Hour of purchase

Month and Year

Total delay time in minutes

Ensured data types were correctly assigned


**📈 Exploratory Data Analysis (EDA)**

🔹 Univariate Analysis

Distribution of ticket class, payment method, and purchase type

Ticket type and journey status distribution

Railcard usage analysis

🔹 Bivariate Analysis

Ticket price vs ticket class

Ticket price vs payment method

Ticket price vs purchase type

Ticket price vs ticket type

🔹 Multivariate Analysis

Ticket price by departure station and delay reason

Combined categorical analysis using grouped bar charts

🔹 Time Series Analysis

Purchases by hour

Monthly revenue trends

Month-year analysis of ticket sales

**📊 Visualizations Used**

Bar Charts

Line Charts

Pie Charts

Histograms

Box Plots

Violin Plots

Scatter Plots

Heatmaps

Stacked Bar Charts

Subplot Dashboards

Interactive Plotly Charts

All visualizations include proper titles, labels, legends, and color schemes for clarity.

**🔍 Key Insights**

🔹 Customer Behavior

Most users prefer online booking

Digital payment methods are widely used

Customers prioritize convenience

🔹 Pricing Strategy

Ticket prices vary mainly by class and ticket type

First-class tickets are significantly more expensive

Payment method and purchase type have minimal impact on pricing

🔹 Time-Based Trends

Booking activity is higher during daytime

Revenue shows monthly fluctuations and seasonal trends

🔹 Passenger Distribution

Few stations act as major travel hubs

Passenger distribution is uneven across stations

🔹 Journey Performance

Most journeys are on time

Delays exist but are relatively limited

No strong relationship between ticket price and delay

🔹 Refund & Railcard Insights

Refund requests are low

Railcard usage is limited but offers potential for growth


**📁 🔷 Repository Structure**

uk-train-data-analysis/
│
├── data/
│   └── train_data.csv
│
├── notebooks/
│   └── eda_analysis.ipynb
│
├── src/
│   ├── data_cleaning.py
│   ├── feature_engineering.py
│   ├── visualization.py
│   └── utils.py
│
├── outputs/
│   ├── charts/
│   └── reports/
│
├── requirements.txt
├── README.md
└── .gitignore

**📂 Project Structure**

uk-train-data-analysis/
│
├── data/
├── notebooks/
├── src/
├── outputs/
├── README.md
├── requirements.txt

**🚀 How to Run the Project**

Clone the repository:
git clone https://github.com/Vijayakrishnantk/UK-Train-Rides-Data-Analysis-Using-Python

Navigate to the project folder:
cd uk-train-rides-data-analysis

Install dependencies:
pip install -r requirements.txt

Run the Jupyter Notebook:
jupyter notebook

**📌 Conclusion**

This project successfully demonstrates how data analytics techniques can be applied to real-world transportation data. 
It highlights patterns in customer behavior, pricing strategies, and operational performance. 
The findings provide valuable insights for improving efficiency and customer experience. 
Data-driven decision-making can significantly enhance railway operations. 
This project showcases practical skills in data cleaning, analysis, and visualization.
