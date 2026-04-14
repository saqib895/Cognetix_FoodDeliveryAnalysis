# Food Delivery Data Analysis (Level 2 Project 2)
## Project Overview
This project analyzes food delivery demand patterns and operational performance using a real-world dataset. It focuses on identifying peak demand times, high-demand areas, and delivery bottlenecks.
---
## Objective 
- Analyze delivery demand patterns
- Evaluate operational performance
- Identify peak ordering hours and high
- demand days
- Detect bottlenecks affecting delivery efficiency
---
## Dataset 
- Source: Zomato Bangalore Dataset
- Link: https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants- Format: CSV
---
## NoteThe dataset does not include order date/time or delivery duration.
- To fulfill task requirements:
- A synthetic datetime column was created
- Delivery time was simulated for analysis
---
## Technologies Used-
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
---
## Project Workflow
### 1. Data Loading
- Loaded dataset using Pandas
- Validated structure using `.info()` and `.shape`
### 2. Data Cleaning
- Removed duplicates
- Handled missing values
- Standardized column names
### 3. Date-Time Processing
- Created synthetic datetime column
- Extracted:  - Hour  
              - Day  
              - Month  
              - Weekday
### 4. Performance Metrics
- Total orders
- Average delivery time
- Maximum & minimum delivery time
### 5. Demand Analysis
- Peak ordering hours- High-demand weekdays- Monthly trends
### 6. Area-wise Analysis
- Orders per location
- High-demand areas
- Average delivery time by area
### 7. Bottleneck Detection
- High delay areas
- Peak hour delays
### 8. Visualization
- Line charts (hourly & monthly trends)
- Bar charts (weekday & area demand)
- Heatmap (hour vs weekday)
---
## Key Insights-
- Certain hours show peak order activity
- Specific areas have higher demand
- Some time periods show higher delivery delays
- Bottlenecks identified during peak hours
---
## Requirements
pip install pandas numpy matplotlib seaborn
---
## How to Run:- 
1. Download the project
2. Install required libraries
3. Open notebook in Jupyter/VS Code
4. Run all cells
5. View outputs and charts
---
## Conclusion
 This project demonstrates real-world data cleaning, time-based analysis, demand pattern identification, and performance evaluation using Python.