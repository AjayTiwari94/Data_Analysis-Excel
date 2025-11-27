# Bike Purchase Analytics Dashboard — Excel Project

## Project Overview
This project showcases end-to-end data analytics using Microsoft Excel, starting from raw customer demographic and lifestyle information related to bike purchases.  
The dataset was cleaned, transformed, and analyzed to build an interactive dashboard that explores buying patterns and helps stakeholders understand what factors influence bike purchases.

![Dashboard Preview](Dashboard_Image.png)

---

## Dataset Description
The dataset contains **1,026 customer records** and includes:

- Customer ID  
- Marital Status  
- Gender  
- Income Level  
- Number of Children  
- Education Level  
- Occupation  
- Home Ownership Status  
- Number of Cars Owned  
- Commute Distance  
- Region  
- Age  
- Purchased Bike (Yes/No)

### Common Issues Found in Raw Data
- Inconsistent text formatting (capitalization & spacing)
- Mixed data types for categorical fields
- Values requiring standardization (distance ranges, gender, education)
- Unnecessary whitespaces
- No structured time-related fields

---

## Data Cleaning & Preparation
Data cleaning was performed using Excel functions, Power Query, and formatting tools:

- Standardized categorical values (e.g., Gender, Marital Status)
- Converted numerical fields to correct number format
- Trimmed spaces and removed inconsistencies
- Ensured column naming consistency
- Validated dataset size, uniqueness, and completeness
- Prepared lookup-friendly tables for interactive reporting

---

## Dashboard Highlights
An interactive Excel dashboard was created using:

- Pivot Tables & Pivot Charts
- Slicers for dynamic filtering
- Card-style KPIs
- Bar Charts, Pie Charts & Line Graphs
- Conditional formatting for insights

### Key Insights Displayed:
- Total customers vs. bike purchasers
- Purchase rate by:
  - Gender  
  - Marital status  
  - Education level  
  - Occupation  
  - Region  
  - Income group  
  - Number of cars owned  
  - Commute distance  
  - Age distribution
- Demographic segments most likely to buy a bike
- Regional demand comparison

---

## Tools & Skills Used
- **Microsoft Excel**
  - Power Query
  - Data Cleaning & Transformation
  - Pivot Tables & Pivot Charts
  - Slicers, Filters & Interactive Components
- **Data Analysis**
- **Dashboard Design**
- **Business Insight Reporting**

---

## Business Questions Answered
- Which customer segment is most likely to purchase a bike?
- Does income level influence buying decisions?
- Are married customers more likely to buy bikes?
- Which region has the highest conversion rate?
- Does commute distance affect bike purchasing?
- How does education or occupation relate to purchase behavior?

---

## Project Structure
```
Bike-Purchase-Excel-Project
│
├── RawData.xlsx
├── CleanedData_and_Dashboard.xlsx
├── Dashboard_Image.png
├── Cleaned_Data_Image.png
└── README.md
```

---

## How to Use
1. Download the dashboard file  
2. Enable editing if prompted  
3. Use slicers (Gender, Region, Education, Commute Distance, etc.) to explore customer behavior  
4. Replace raw data and refresh pivots for updated insights

---

## Future Enhancements
- Predictive modeling (who is most likely to buy?)
- Integration with Power BI for deeper analytics
- Automated monthly dataset refresh
- Additional metrics such as revenue and model types

---

## License
This repository is released under the MIT License. See `LICENSE` for details.

## Author: 
- Ajay Tiwari
- B.Tech - Computer Science and Engineering (Artificial Intelligence): 2022-26

