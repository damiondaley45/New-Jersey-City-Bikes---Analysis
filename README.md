# 2024 New Jersey CitiBike Data Analysis Project
# LinkedIN: [Damion Daley](www.linkedin.com/in/damiondaley)
# Project Overview

This project involves collecting, cleaning, transforming, and analyzing 2024 YTD New Jersey CitiBike data. The data was scraped using Python, processed through various data transformations, and visualized in an interactive Power BI dashboard. The goal is to provide insights into biking trends, trip characteristics, and user behaviors across the CitiBike network.
![Screenshot 2024-11-10 001356](https://github.com/user-attachments/assets/5a8c036b-30c1-4bee-973c-3c6ae0411720)
#Features

# Data Collection & Pre-Processing

Data Collection: CitiBike data for the year 2024 (year-to-date) was scraped using Python, loaded, and concatenated.
Pre-Processing:
Checked for missing values and handled them appropriately.
Removed duplicated records to ensure data integrity.

# Data Transformation

Column Standardization:
Converted column headers to a standard format and ensured datatypes are consistent.
Renamed columns for clarity and consistency.

# Calculated Columns:

Distance: Calculated in miles using the latitude and longitude coordinates of start and end points.
Trip Duration: Calculated in minutes and seconds based on the start and end datetime.
Average Speed: Derived from distance and duration to analyze user speed patterns.
Time of Day Classification: Categorized trips into morning, noon, and other time blocks for time-based analysis.
Visualization & Dashboard

# Power BI Dashboard: 

Created a Power BI .pbix file to visualize key metrics and trends in the CitiBike data.
DAX Measures: Defined calculated measures in DAX to support visual elements, enhancing insights through custom aggregations.
PowerPoint: Designed SVG files for custom dashboard visuals, allowing for a cleaner, visually appealing dashboard layout.
Technology Stack

# Python Packages:

Pandas - for data manipulation and preprocessing
Glob - for file handling and directory traversal
NumPy - for numerical calculations and array manipulation
Dask - for handling large datasets and efficient processing

# Power BI: 
Interactive data visualization and dashboard creation.

# DAX:
Used in Power BI for creating custom measures.

# PowerPoint:
SVG creation for dashboard canvas.
## Git: Version control to manage script changes and post-project updates to GitHub.

### Installation and Setup

Clone the repository:
git clone https://github.com/cruise345/2024-citibike-data-analysis.git
Install the required Python packages:
pip install pandas glob numpy dask
Open the Power BI .pbix file to explore the dashboard.
# Usage

Run the Python scripts to load, preprocess, and transform the data.
Open the Power BI file to view and interact with the data visualization dashboard.
Adjust or customize the Power BI visuals as needed.
Contributing

Feel free to fork this repository, create a branch, and submit pull requests if you'd like to contribute!
