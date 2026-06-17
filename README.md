# PhonePe-Transaction-Insights-Dashboard 
**📊 PhonePe Pulse Data Visualization Dashboard**

**📌 Project Overview****

This project is a Streamlit-based interactive dashboard built using the PhonePe Pulse dataset.

It visualizes digital payment trends in India, including transactions, users, insurance, and geographic insights.

The dashboard helps to understand how digital payments are growing across different states and time periods.
________________________________________
**Problem Statement****

With the rapid growth of digital payment platforms like PhonePe, analyzing transaction, user and insurance is essential to understand digital adoption trends across India. This project aims to build a dashboard using PhonePe Pulse data to visualize transaction growth, user engagement, insurance performance, and state-wise digital payment activity.
The dashboard helps identify top-performing states, analyze user and transaction patterns, monitor insurance adoption, and generate meaningful insights that support data-driven decision-making in India's digital payment ecosystem.
________________________________________
**🎯 Objectives**

•	Analyze PhonePe transaction trends across India. 

•	Study user growth and digital payment adoption. 

•	Evaluate insurance usage and growth patterns. 

•	Visualize state-wise transaction and user distribution. 

•	Identify top-performing states and regions. 

•	Generate meaningful business insights from PhonePe Pulse data.
________________________________________
**📂 Dataset Used**
•	PhonePe Pulse open-source dataset 

•	Aggregated transaction data (count & amount) 

•	User data (registered users & device brands) 

•	Insurance data (count & amount) 

•	State, district, and pin-code level data 

•	Year-wise and quarter-wise records
________________________________________
**🛠️ Technologies Used**

•	Python

•	Streamlit (Dashboard UI)

•	SQLite (Database)

•	Pandas (Data processing)

•	Matplotlib / Seaborn (Graphs)

•	Plotly (Maps)

•	ETL (Extract, Transform, Load)

________________________________________
**Data Extraction & Database Setup**

**Data Extraction**

•	Cloned the PhonePe Pulse GitHub repository containing transaction data.

•	Extracted raw data from different folders (transaction, user, insurance).

•	Loaded the cleaned data into a structured SQL database.

**SQL Database and Table Creation**

•	Created a relational database using SQL (SQLite).

•	Organized data into structured tables for easy analysis and querying.

**Table Structure**

**1. Aggregated Tables**

•	aggregated_user → Stores aggregated user-related data

•	aggregated_transaction → Contains transaction amounts and counts

•	aggregated_insurance → Stores insurance transaction data

**2. Map Tables**

•	map_user → User distribution data across states

•	map_transaction → State and district-level transaction data

•	map_insurance → Insurance mapping data across regions

**3. Top Tables**

•	top_user → Top users by state/district/pincode

•	top_transaction → Top-performing states, districts, and pincodes

•	top_insurance → Top insurance performance data
________________________________________
**📊 Features of Dashboard**

**🏠 Home Page**

•	Project overview

•	Key metrics (transactions, users, insurance)

•	Project workflow

**💳 Transactions Analysis**

•	Shows year-wise growth of transaction amount. 

•	Displays top states by transaction volume. 

•	Analyzes quarterly transaction trends. 

•	Compares state-wise transaction performance. 

**👥 User Analysis**

•	Shows state-wise total users distribution.

•	Displays device brand usage pattern. 

•	Analyzes year-wise growth of registered users. 

•	Compares user adoption across states. 

**🛡️ Insurance Analysis**

•	Shows state-wise insurance count distribution. 

•	Displays top states by insurance amount.

•	Analyzes year-wise insurance growth trends. 

**🌍 Geographic Insights**

•	India map visualization

•	State-wise transaction heatmap

•	Regional performance analysis

**📌 Insights & Findings**

•	Key business insights

•	Growth patterns

•	Observations and conclusions
________________________________________
**📈 Key Insights**

•	Digital transactions are increasing year by year

•	Maharashtra, Karnataka, Telangana are top performing states

•	Mobile payments are dominated by a few states

•	Insurance adoption is still growing

•	Urban regions lead in digital payment usage
________________________________________
🏗️ Project Structure
```
PhonePe Pulse GitHub Dataset
            ↓
      JSON Files
            ↓
     Python Extraction
            ↓
      SQLite Database
            ↓
      9 SQL Tables
            ↓
    Data Analysis (Pandas)
            ↓
 Streamlit Dashboard
            ↓
 Business Insights
```
________________________________________
**🎯 Final Note**

This project demonstrates how data visualization can be used to understand India's digital payment ecosystem using interactive dashboards.
