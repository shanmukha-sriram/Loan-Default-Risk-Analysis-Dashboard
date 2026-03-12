  "Loan Default & Financial Risk Analysis"

Dashboard Link :  https://app.powerbi.com/links/DYoHX5DSyh?ctid=e7aa10ff-3a86-4274-a7f4-788b45a666bd&pbi_source=linkShare&bookmarkGuid=43987964-afdd-41db-b62f-b34fc64e87d8

Problem Statement

This dashboard helps financial institutions understand loan distribution, applicant demographics, and financial risk patterns. It enables lenders to identify high-risk borrower segments and monitor loan default trends over time.

Through this dashboard, analysts can evaluate how employment type, credit score, age group, education level, and marital status influence loan amounts and default probabilities.

The dashboard also provides insights into Year-over-Year changes in loan amounts and defaulted loans, helping financial institutions make better lending decisions and risk management strategies.

Since the default rate varies significantly across employment categories and credit score levels, banks can focus on improving their risk assessment models for high-risk applicant groups.

Steps followed

Step 1 : Load data into Power BI Desktop, dataset was connected through Power BI Dataflows.

Step 2 : Open Power Query Editor and under the View Tab, enable
Column Distribution, Column Quality, and Column Profile to understand the data structure.

Step 3 : Column profiling was changed from based on top 1000 rows to entire dataset to ensure accurate data quality analysis.

Step 4 : Data transformation steps were applied where necessary to ensure consistent data types and remove anomalies.

Step 5 : Relationships between tables were created in the data model view to support accurate calculations and analysis.

Step 6 : In the Report View, a custom theme and layout was applied to maintain consistent visual design across the dashboard.

Step 7 : Multiple visuals were created to represent loan distribution and financial metrics, including line charts, area charts, donut charts, and decomposition trees.

Step 8 : Slicers were added for Income Bracket and Employment Type to enable dynamic filtering across the report.

Step 9 : Area charts were used to represent Loan Amount by Purpose, showing distribution across categories such as Home, Business, Education, Auto, and Others.

Step 10 : Line charts were used to represent Average Income by Employment Type and Default Rate (%) by Employment Type.

Step 11 : A line chart was created to visualize Average Loan Amount by Age Group, highlighting loan patterns among different demographic groups.

Step 12 : Another time-series chart was created to show Default Rate (%) by Year to analyze changes in default behavior over time.

Step 13 : A donut chart was added to represent Average Loan Amount by Credit Score across Age Groups and Marital Status.

Step 14 : A stacked column chart was used to analyze Loan Amount for Middle Age Adults based on Mortgage and Dependents status.

Step 15 : A visual was created to show Number of Loans by Education Type, highlighting the educational background of borrowers.

Step 16 : A Year-over-Year Loan Amount Change chart was developed using DAX calculations to analyze growth or decline in loan disbursement.

Step 17 : Another visual was created to show Year-over-Year Default Loan Amount Change, helping identify risk trends.

Step 18 : A Sankey Chart was implemented to visualize the flow of Loan Amount across Credit Score Bins and Marital Status.

Step 19 : A Decomposition Tree was used for root-cause analysis to break down Loan Amount by Income Bracket and Employment Type.

Step 20 : The report was finally published to Power BI Service for sharing and interactive analysis.

Snapshot of Dashboard (Power BI Service)

  <img width="1919" height="1089" alt="Image" src="https://github.com/user-attachments/assets/4d69b7af-1acf-427d-a8c7-7911166d514f" />


Report Snapshot (Power BI Desktop)

 <img width="1919" height="1095" alt="Image" src="https://github.com/user-attachments/assets/c7595638-3c93-4093-8773-a14996540a27" />
 
Insights

A multi-page Power BI report was created and published to Power BI Service.
Following insights can be derived from the dashboard.

[1] Loan Distribution by Purpose

Home loans represent the largest loan amount category.

Business and Education loans follow next in terms of loan volume.

Auto and other purposes account for relatively smaller loan amounts.

[2] Default Risk by Employment Type

Unemployed applicants show the highest default rate (~3.39%).

Full-time employees have the lowest default rate (~2.36%).

Self-employed and part-time employees fall in between.

This suggests that employment stability plays an important role in loan repayment behavior.

[3] Loan Amount by Age Group

Adults receive the highest average loan amount (~127K).

Middle-aged and senior citizens receive slightly lower loan amounts.

Teen borrowers represent the lowest loan amount group.

[4] Loan Distribution by Education Level

Borrowers with Bachelor's degrees account for the highest number of loans.

High school graduates follow next.

Master's and PhD holders have relatively fewer loan counts.

[5] Default Rate Trend Over Time

Default rates fluctuate across years.

A peak default rate of approximately 11.75% was observed in 2016.

Default rates later declined and stabilized.

This trend helps institutions analyze historical risk fluctuations.

[6] Financial Risk Metrics

Year-over-Year Loan Amount Change shows variations in lending patterns.

Year-over-Year Default Loan Change highlights fluctuations in financial risk.

Sankey Visualization helps track loan flow across credit score categories and marital status.

[7] Loan Amount Distribution by Credit Score

Applicants with medium and high credit scores account for the majority of loan amounts.

Very low credit score segments contribute less to overall loan distribution.

⭐ This project demonstrates the use of Power BI for financial risk analytics, data storytelling, and interactive dashboard design.
