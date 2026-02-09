# HR_-ANALYSIS_BI_RM

# HR Analytics Dashboard (Power BI)

## Overview
This project analyzes employee attrition to better understand why employees leave a company and which factors are most strongly associated with turnover. The dashboard is designed to help HR teams identify attrition patterns and consider how future hiring and retention strategies can be informed by data-driven insights.

The primary focus of this project was to translate business questions into clear, interpretable visuals while building a strong foundation in Power BI dashboard design and KPI development.


## Dataset
The dataset used in this project is an HR employee dataset containing approximately 1,470 employee records. It includes information related to employee demographics, education background, job roles, salary ranges, overtime status, tenure, and attrition outcomes.

The data was originally provided in Excel format and required cleaning, formatting, and preparation prior to visualization.


## Key KPIs
- Total Employees  
- Total Attrition  
- Attrition Rate (%)  
- Retention Rate (%)  


## Dashboard Overview
The dashboard provides a comprehensive view of employee attrition across multiple dimensions, including age group, education field, salary range, job role, overtime status, years at the company, and gender. Interactive slicers allow users to segment the data and compare attrition patterns across different employee groups.


## Analysis & Insights

The company demonstrates a strong overall retention profile, with an attrition rate of approximately 16%, indicating that the majority of employees remain with the organization. This suggests that retention challenges are targeted rather than systemic.

Attrition by education field shows that employees with backgrounds in Life Sciences, Medical, and Marketing account for a large portion of total attrition. Rather than drawing immediate conclusions, this highlights areas for further investigation, such as whether early departures are influenced by age group, workload, or department-specific expectations.

Attrition by age group is highest among employees between the ages of 26 and 35, which aligns with typical career behavior where individuals are more likely to explore new opportunities or make career changes. Attrition decreases steadily with age, suggesting increased stability and long-term commitment among older employees. A smaller but noticeable level of attrition among younger employees reflects early-career exploration.

Analysis of attrition by tenure shows that the first year of employment is the most critical period for employee retention. Attrition declines after the first year but shows smaller increases around the three- to five-year range and again near the ten-year mark, which may correspond to career reassessment or promotion-related decision points. Long-tenured employees beyond these stages show consistently lower attrition.

Overtime is also a significant factor. Employees who work overtime exhibit higher attrition compared to those who do not, suggesting that workload management and burnout prevention may play an important role in improving retention outcomes.


## Gender-Based Attrition Analysis

When the dashboard is segmented by gender, male employees show a higher overall attrition rate compared to female employees. While this is partially influenced by a larger male employee population, attrition remains more pronounced among males even after segmentation.

Salary range appears to play a stronger role in retention for female employees. As compensation increases, female attrition declines more sharply, suggesting that competitive pay may be an important retention factor. Lower salary bands show higher attrition among female employees, while higher salary ranges demonstrate stronger retention.

For male employees, attrition declines more gradually over time, with a sustained risk of turnover between the three- and five-year mark. This suggests that factors beyond compensation, such as workload, career progression, or role satisfaction, may have a greater influence on retention decisions.

---

## Job Role and Gender-Based Insights

When attrition is examined by job role and gender, clear differences emerge. Male attrition is distributed across multiple roles, particularly Laboratory Technician and Sales Executive positions, indicating that turnover is not concentrated in a single function.

In contrast, female attrition is more heavily concentrated in sales roles, with other positions showing relatively lower attrition counts. This suggests that role-specific pressures, such as performance expectations, compensation structure, or work-life balance, may impact employees differently by gender.

These patterns highlight the importance of role-specific retention strategies rather than one-size-fits-all solutions.


## Conclusion
Overall, this dashboard identifies key attrition drivers related to tenure, salary range, overtime, job role, age group, and gender. While the company maintains strong overall retention, specific employee segments present higher turnover risk.

The dashboard provides a strong foundation for understanding where attrition is occurring and highlights several areas where deeper analysis could further support HR decision-making.


## Opportunities for Future Analysis

This dashboard provides a strong foundation for understanding employee attrition, but several opportunities exist for deeper analysis as additional data and skills are applied.

Future analysis could explore the interaction between gender, job role, and overtime to better understand workload-related attrition patterns. Examining salary progression over time, rather than salary bands alone, could also provide insight into long-term retention behavior.

Additional segmentation by department, tenure milestones, and promotion history may help identify specific points where employees are more likely to leave. Incorporating performance metrics, engagement scores, or manager-level data could further strengthen retention insights.

As Power BI skills advance, future iterations of this project could include more advanced DAX measures, trend comparisons over time, and predictive indicators to proactively identify high-risk employee groups.

---

## Project Context

This project was completed immediately after finishing a four-hour *Introduction to Power BI* course on DataCamp. The goal was to actively apply newly learned concepts, including data modeling, visual selection, KPI creation, Power Query transformations, filtering, and basic DAX, in a practical, real-world scenario.

Rather than focusing on advanced calculations, the emphasis of this project was on translating business questions into meaningful visuals, validating assumptions through segmentation, and building a clear, executive-style dashboard. This project reflects a hands-on learning approach and serves as a baseline for future Power BI development.


## Tools Used
- Power BI  
- Power Query  
- DAX (basic measures)  
- Excel (data cleaning, formatting, duplicate removal, and initial exploration)  
- Data visualization and dashboard design  

## Repository Contents
- Power BI dashboard file (`.pbix`)
- Dataset (Excel format)
- Dashboard screenshots
- README documentation
