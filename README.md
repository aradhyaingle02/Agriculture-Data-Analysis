# Agriculture Data Analysis Dashboard (AWS + Snowflake + Power BI) 🌾📊

**Project Overview**
This project implements a complete Cloud Data Analysis Pipeline using AWS S3 for storage, Snowflake ❄️ for scalable warehousing and transformation, and Power BI for dynamic visualization. The goal was to analyze agricultural data, focusing on the impact of Rainfall 🌧️, Temperature 🌡️, Humidity, and Year on Crop Yields across different locations and seasons.

The pipeline successfully moved raw data from S3, loaded it into Snowflake, performed extensive SQL transformations, and then connected Power BI to Snowflake for report development and publishing.

**Architecture and Key Technologies 🛠️**

1)Cloud Storage	AWS S3:	Used S3 bucket (powerbi.project) to securely store the raw data file (data_season.csv).

2)Cloud Warehousing	Snowflake ❄️:	Configured Storage Integration and AWS IAM Role for secure connection between S3 and Snowflake. Loaded data using the COPY INTO command.

3)Data Transformation (ELT):	Snowflake SQL,	Performed extensive data cleaning and feature engineering, including creating categorical columns (year_group, rainfall_groups) using conditional SQL updates.

4)Data Visualization:	Power BI Desktop & Service 📊,	Connected directly to the transformed data in Snowflake. Developed a multi-page interactive report for deep-dive analysis.

5)Deployment:	Power BI Service ☁️,	Published the final report to the cloud service for viewing and sharing.

**Dashboard Features & Analysis**
The Power BI report consists of four dedicated analysis pages, providing key insights:

Rainfall Analysis 🌧️: Visualizes average rainfall by Year, Season, Crop, and Location.

Temperature Analysis 🌡️: Shows the distribution and averages of temperature.

Humidity Analysis: Focuses on humidity trends.

Yield Analysis 🌱: Correlates environmental factors (Rainfall, Temp, Humidity) with crop yields.

**Visualization Highlights:**
1)Customized charts with adjusted titles, axes, and data labels for enhanced readability.

2)Application of different report themes for visual appeal.

**Repository Files 📁**
data_season.csv: The original dataset used for the project.

**Screenshots of the key dashboard pages.**
