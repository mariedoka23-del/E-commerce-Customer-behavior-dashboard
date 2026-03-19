

# E-commerce Customer Behavior Dashboard – Power BI

## Project Overview

This interactive Power BI dashboard analyzes customer behavior in an e-commerce environment using a dataset of 350 customers. The goal is to uncover patterns in spending, satisfaction, loyalty (membership tiers), geographic performance, discount impact, recency, and gender differences — turning raw data into actionable business insights.

Built as a personal portfolio project to demonstrate data visualization, DAX measures, dashboard design, and business storytelling skills.

**Key questions answered:**
- Which customer segments spend the most?
- How does satisfaction relate to lifetime value?
- Do discounts help or hurt long-term revenue?
- Which cities are performing best/worst?
- Is there a churn risk signal from recency?

## Dashboard Features

- **Two main pages**:
  - **Page 1 – Executive Overview**  
    KPI cards (total customers, total spend, avg items, % satisfied, % with discount)  
    Stacked bar: Total Spend by Membership Type and City  
    Pie chart: Satisfaction Level distribution  
    Gender items purchased donut  
  - **Page 2 – Deep Dive & Correlations**  
    Scatter: Avg Total Spend vs Avg Rating by Satisfaction Level  
    Matrix: Avg Spend by City and Satisfaction Level  
    Scatter/line: Total Spend/Items Purchased vs Days Since Last Purchase (recency) by Membership Type

- **Interactivity**  
  Slicers for: City, Gender, Membership Type, Satisfaction Level, Discount Applied

- **Visual styles**  
  Grey background for clean, professional look  
  Consistent color palette (purple/orange/blue tones)  
  Clear, shortened titles (business language)

## Key Business Insights

### From Dashboard
- **Membership tiers create strong value segmentation**  
  Gold members generate the highest total and average spend (especially in San Francisco and New York). Bronze contributes the least → clear opportunity to convert Silver → Gold.

- **Satisfaction is a major revenue driver**  
  Satisfied customers show significantly higher average spend (upward trend in scatter plot). ~36% Satisfied vs ~31% Unsatisfied → 64% not fully satisfied is a red flag.

- **Geographic concentration**  
  San Francisco and New York lead in spend and satisfaction; Chicago and Houston lag noticeably → regional strategy needed.

- **Gender nuance**  
  Females purchase slightly more items on average (57.3% vs 42.7%), though total spend difference is minimal.

### From Raw Data (Additional Observations)
- **Discounts appear counterproductive**  
  Customers without discounts have ~15% higher average spend and better satisfaction skew.

- **Recency = churn risk**  
  Moderate negative correlation (-0.54) between Days Since Last Purchase and Total Spend → customers inactive 40–60+ days have significantly lower lifetime value.

- **Gold loyalty program success**  
  Gold members achieve very high average ratings (~4.68/5) → strong evidence the program drives both spend and happiness.

## Tools & Skills Demonstrated

- Power BI Desktop
- Data modeling & relationships
- DAX measures (percentages, averages, dynamic calculations)
- Visualizations: KPI cards, bar/column charts, pie/donut, scatter plots, matrix, slicers
- Conditional formatting (planned / optional)
- Dashboard layout & design principles (grey theme, consistent colors, business titles)
- Business insight extraction & storytelling

## How to Use / Explore

1. Clone or download this repository
2. Open `E-commerce Customer Behavior.pbix` in **Power BI Desktop**
3. Interact with slicers to filter by city, membership type, satisfaction, etc.
4. Hover over visuals for detailed tooltips

## Future Improvements / Ideas

- Include a map visual for cities (bubble size = spend)
- Box plots for spend distribution by membership/city (spread & outliers)
- What-if parameter for discount simulation
- Decomposition tree for root-cause analysis of low satisfaction

## About the Project

Personal learning & portfolio project created in early 2026.  


