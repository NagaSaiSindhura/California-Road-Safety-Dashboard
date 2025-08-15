**Road Injuries in California – An Exploratory Analysis using BI Tools**

This project presents an exploratory analysis of road injuries in California, leveraging data visualization and BI tools to uncover patterns, trends, and actionable insights. The goal is to support data-driven decision-making that can help reduce accidents, casualties, and economic losses.

**🎯 Business Problem******

California consistently records higher road accident rates compared to other US states. These accidents result in significant human and financial costs.

**Primary objectives:**

1.Reduce the number of accidents.

2.Lower casualty rates.

3.Minimize economic impact.

The project uses archival data to identify trends, patterns, and root causes to guide preventive strategies.

****The analysis focuses on answering key decision-making questions:**

1.Which modes of transportation cause the most casualties?

2.How does accident frequency vary by time of day?

3.Which counties and regions in California have the highest accident rates?

4.What is the trend in injuries over the years?

5.What are the severity levels and their distributions?

**📂 Dataset Description**

The dataset contains detailed information on road accidents in California, including:

1.reportyear – Year of report

2.county_name – County where the accident occurred

3.region_name – Region within California

4.mode – Mode of transportation involved

5.severity – Severity of the accident

6.injuries – Number of injuries

7.totalpop – Total population in that region

**🛠 Data Cleaning & Preparation****

Data cleaning was performed using Python libraries:

1.Missing values replaced using mean (for numerical) and mode (for categorical).

2.Unwanted rows removed.

3.Dataset normalized for efficient visualization in Power BI.

**🔗 Database Integration**

The cleaned dataset was stored in MySQL and connected to Power BI for dashboard creation.
Steps:

1.Load cleaned data into MySQL.

2.Configure MySQL–Power BI connector.

3.Import and visualize data.

**📊 Key Insights from Dashboards**

1.Cars cause more casualties than other transport modes.

2.Nighttime (early & late night) sees more accidents than mornings/afternoons.

3.Injuries are decreasing gradually every year.

4.Los Angeles county records the highest number of casualties on average.

5.Around 25% of casualties are fatal.

**📌 Data-Driven Recommendations**

**Night Driving Safety:****

1.Limit non-essential nighttime travel.

2.Improve road lighting and visibility.

3.Educate drivers on fatigue risks.

**High-Risk Area Focus:**

1.Increase law enforcement.

2.Improve road infrastructure.

3.Launch awareness campaigns.

****Further Analysis Opportunities:**

1.Correlate accidents with weather data.

2.Identify accident hotspots using geospatial analysis.

3.Study demographic risk factors.

4.Evaluate severity patterns by time & location.

**✅ Conclusion**

A strategic, data-driven approach to road safety in California can help reduce injuries and fatalities. 
Concentrating efforts on high-risk regions and dangerous time windows—combined with enforcement, infrastructure improvements, and targeted awareness—will make California’s roads safer for all.
