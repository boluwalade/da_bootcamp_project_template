# Analyzing yearly sales and profit data for an Online Store
---
![DAB- S  P Dashboard](https://github.com/user-attachments/assets/629b88a9-8749-4e87-ab4e-e64be5653001)
![click to view dashboard](link-to-dashboard)
## Project Overview

Provide a brief introduction to the project, its goals, and its context.

*Example:*  
In this project, I analyzed the CMS Payroll-Based Journal (PBJ) Daily Nurse Staffing dataset for Q1 2024. The goal was to examine staffing patterns in long-term care facilities, focusing on compliance with federal staffing mandates and identifying trends that could affect care quality.

---

## Objective(s)

Clearly state the key objectives of the analysis. These should align with what you aim to achieve with the data.

*Example:*  
The primary objectives of this project are:
- To assess the adequacy of nurse staffing levels in long-term care facilities.
- To identify facilities that fall below the mandated staffing thresholds.
- To uncover potential correlations between staffing shortages and care quality metrics.

---

## Dataset(s)

Describe the dataset(s) used, including its source, size, and any relevant characteristics. Mention how you cleaned or processed the data if necessary.

*Example:*  
The dataset used in this project is the CMS Payroll-Based Journal (PBJ) Daily Nurse Staffing dataset for Q1 2024. This dataset includes:
- **Source**: Centers for Medicare & Medicaid Services (CMS).
- **Size**: Over 50,000 records from more than 15,000 facilities.
- **Features**: Facility ID, daily nurse staffing hours, total nurse count, staffing classification (RN, LPN, CNA), and facility location.

Data cleaning involved removing duplicates, handling missing values, and converting time-based columns to a usable format.

---

## Tools & Technologies

List the tools, programming languages, or software you used to perform the analysis.

*Example:*  
- **Python**: Pandas for data manipulation, Matplotlib/Seaborn for visualization.
- **SQL**: Used for querying the dataset from the CMS database.
- **Jupyter Notebooks**: To document the analysis and run code interactively.
- **Tableau**: For creating interactive dashboards to visualize trends.

---

## Methodology

Explain the steps taken to analyze the data, from data preparation to insights. This could include the specific analyses performed (e.g., statistical tests, visualizations).

*Example:*  
1. **Data Cleaning**: Removed null entries and aggregated daily staffing data by facility and month.
2. **Descriptive Analysis**: Generated summary statistics to understand staffing distributions.
3. **Compliance Analysis**: Compared staffing levels against the minimum staffing requirements set by CMS.
4. **Correlation Analysis**: Used regression models to explore the relationship between staffing levels and facility quality ratings.
5. **Visualization**: Created line charts and heatmaps to show staffing trends and facilities that consistently fell below the threshold.

---

## Results & Insights

Present key findings or insights that were derived from the analysis. Use bullet points or a narrative to explain what you discovered.

*Example:*  
- 20% of long-term care facilities consistently failed to meet the required staffing thresholds.
- Facilities with lower staffing levels showed a 15% higher likelihood of receiving below-average quality ratings.
- Rural facilities were more likely to have staffing shortages compared to urban ones.

---

## Challenges

Highlight any challenges encountered during the project and how you overcame them (e.g., data quality issues, missing values, etc.).

*Example:*  
One major challenge was the inconsistency in reporting between different facilities. Some facilities had incomplete data for certain days, which required imputation techniques to estimate missing staffing levels.

---

## Conclusion & Next Steps

Summarize the main takeaways from the project and outline potential future steps to build on the analysis.

*Example:*  
This analysis highlighted the impact of staffing shortages on the quality of care in long-term care facilities.
Future work could include exploring the relationship between staffing trends and patient outcomes, or expanding the dataset to include multiple quarters to examine long-term trends.

---

## References

List any sources, papers, or datasets you referred to during the project.

*Example:*  
- Centers for Medicare & Medicaid Services (CMS) – PBJ Dataset
- [CMS Staffing Requirements](https://www.cms.gov/regulations-and-guidance/)
