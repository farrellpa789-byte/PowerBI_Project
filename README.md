[power_bi_dashboard_readme.md](https://github.com/user-attachments/files/34256437/power_bi_dashboard_readme.md)
# Data Visualization: Tech Layoffs Power BI Dashboard

## 📊 Project Overview

This is the final phase of the Tech Layoffs Data Analysis project. After cleaning the raw data and performing Exploratory Data Analysis (EDA) using SQL, the structured dataset was imported into **Power BI** to create an interactive, dynamic dashboard. 

The goal of this dashboard is to make the insights accessible to non-technical stakeholders, allowing them to visually explore the impact of the global tech layoffs by time, geography, industry, and company stage.

## 🛠️ Tools & Technologies Used

* **Business Intelligence Tool:** Microsoft Power BI (`.pbix`)
* **Data Processing:** Power Query
* **Calculations & Measures:** DAX (Data Analysis Expressions)
* **Data Source:** Cleaned MySQL dataset (`layoffs_staging2`)

## 📈 Dashboard Key Features & Visualizations

The dashboard provides a comprehensive overview of the layoff crisis through the following key metrics and visuals:

### 1. High-Level KPIs (Cards)
* **Total Employees Laid Off:** A prominent display of the overall human impact.
* **Total Companies Affected:** Count of unique organizations that conducted layoffs.
* **Average Layoff Percentage:** The average proportion of workforce reduced across affected companies.

### 2. Temporal Trends (Line / Area Charts)
* **Layoffs Over Time (Monthly/Yearly):** Visualizes the peaks and valleys of layoffs over the available timeline, highlighting the most severe months of the crisis based on our SQL rolling total analysis.

### 3. Categorical Breakdowns (Bar / Column Charts)
* **Hardest Hit Industries:** Compares total layoffs across sectors (e.g., Consumer, Retail, Crypto).
* **Impact by Company Stage:** Analyzes whether early-stage startups or Post-IPO giants suffered heavier losses.
* **Top Companies:** A focused view on the specific companies with the highest absolute number of layoffs.

### 4. Geographical Impact (Map Visual)
* **Global Layoff Distribution:** An interactive map highlighting the countries and specific regions most affected by the tech downturn.

### 5. Interactive Slicers
* Users can filter the entire report by **Year**, **Country**, and **Industry** to drill down into specific micro-trends.

## 🚀 How to Use / View This Project

1. Ensure you have [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed on your machine.
2. Download the `.pbix` file from this repository.
3. Open the file in Power BI Desktop to interact with the dashboard, filter the data, and explore the underlying Data Model and DAX formulas.

*(Note: Add a screenshot or GIF of your Power BI Dashboard here to give viewers an immediate look at your work without needing to download the file!)*

## 💡 Conclusion

By transitioning from raw SQL data manipulation to Power BI visualization, this project demonstrates a complete end-to-end data analytics workflow. The resulting dashboard transforms thousands of rows of layoff data into a clear, interactive story that highlights the realities of the global tech industry's downturn.
