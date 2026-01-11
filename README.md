
## Customer Shopping Behavior Analysis
This repository contains a comprehensive data analysis project that explores customer purchasing patterns across 3,900 transactions. By integrating Python for data engineering, PostgreSQL for business intelligence, and Power BI for visual storytelling, this project uncovers actionable insights into spending habits, demographics, and product performance.





### 🚀 Project Workflow
1. Data Engineering (Python)

Cleaning: Handled 37 missing values in the "Review Rating" column by imputing the median rating for each product category.



Standardization: Converted all columns to snake_case for database compatibility.


Feature Engineering: Created an age_group column and binned purchase frequencies to enhance segmentation analysis.


Integration: Connected to a PostgreSQL database to load the cleaned dataset for structured analysis.

2. Business Intelligence (SQL)
Using PostgreSQL, I performed deep-dive analysis to answer critical business questions, including:


Revenue by Gender: Identified that Male customers generate significantly more revenue ($157,890) than Female customers ($75,191).



Shipping Impact: Discovered that customers using Express Shipping have a higher average spend ($60.48) compared to Standard Shipping ($58.46).



Discount Dependency: Analyzed products like Hats (50%) and Sneakers (49.66%) that have the highest rates of discounted purchases.


Segmentation: Classified the customer base into Loyal (3,116), Returning (701), and New (83) segments.

3. Interactive Visualization (Power BI)
I developed a dynamic dashboard to track real-time KPIs and behavioral trends.


Key Dashboard Metrics:


Total Customers: 3,900 

Avg. Purchase: $59.76 

Avg. Rating: 3.75 / 5.0 


Subscriber Mix: 27% Yes / 73% No 


### 📈 Key Findings

Top Revenue Driver: Young Adults are the most valuable age segment, contributing $62,143 in total revenue.



Category Leaders: Clothing and Accessories are the top-performing categories by both revenue and sales volume.




Subscription Opportunity: While only 27% of customers are subscribers, their average spend is nearly identical to non-subscribers ($59.49 vs $59.87), indicating a massive opportunity for loyalty conversion.

### 💡 Strategic Recommendations

Targeted Marketing: Focus acquisition efforts on the Male demographic and Young Adult age groups to maximize ROI.



Loyalty Conversion: Implement reward programs to move the 701 "Returning" customers into the "Loyal" segment.


Shipping Incentives: Promote Express Shipping or "Next Day Air" for high-value items, as these users demonstrate higher spending power.



Subscription Growth: Launch exclusive benefits (early access, special discounts) to convert the 73% non-subscriber base.

### 📁 Repository Structure
data/: Raw and cleaned datasets.

notebooks/: Python scripts for cleaning and EDA.

queries/: SQL files for PostgreSQL business analysis.

dashboard/: Power BI file (.pbix) and dashboard screenshots.

