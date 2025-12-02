# PRIME-TRUST INSURANCE DASHBOARD

### Dashboard Link : https://app.powerbi.com/links/hAcrDtl7TH?ctid=9f29f7b9-493c-45c8-adf8-2ce2ff707b11&pbi_source=linkShare

## Problem Statement

This dashboard provides a comprehensive overview of the insurance company’s key business metrics, enabling better decision-making across policy performance, customer activity, and claims management. It helps the organization analyze premium amounts, claim amounts, coverage distribution, customer status (active/inactive), gender distribution, and policy-wise claim summaries.

With insights into premium contribution by policy type, claim trends by age group, and claim status patterns, the company can identify high-performing policy categories, detect risk-prone customer segments, and understand claim settlement efficiency.

The dashboard also highlights active vs inactive customers, allowing the company to focus on customer retention strategies. Additionally, the breakdown of rejected, settled and pending claims can help in improving the claim settlement process and customer satisfaction.


### Steps followed 

- Step 1: Loaded the insurance dataset into Power BI Desktop.

- Step 2: Opened Power Query Editor and enabled Column distribution, Column quality, and Column profile options for complete data understanding.

- Step 3: Set column profiling to use the entire dataset instead of the default 1000 rows.

- Step 4: Verified that most columns had clean data; necessary transformations were applied to numeric fields like Premium Amount, Claim Amount, and Coverage Amount.

- Step 5: Removed null values for accurate calculation of aggregated values such as premium, claims, and coverage.

- Step 6: Applied a custom energy-themed dashboard color palette for a modern, energetic visual identity aligned with the “insurance & finance” domain.

- Step 7: Added slicers for:

    Policy Number

    Claim Number

    Customer ID
    
    to enable interactive filtering.

- Step 8: Created KPI Card visuals for:

    Total Premium Amount

    Total Claim Amount

    Total Coverage Amount

- Step 9: Added bar chart visual for Premium Amount by Policy Type (Travel, Health, Auto, Life, Home).

- Step 10: Added doughnut chart showing Active vs Inactive Customer Count with % contribution.

- Step 11: Added column chart showing Number of Claims by Claim Status (Rejected, Settled, Pending).

- Step 12: Added line area chart for Claim Amount by Age Group (Adults, Elder, Younger Adults).

- Step 13: Added table visual summarizing policy-wise claim amounts for Pending, Rejected, and Settled categories.

- Step 14: Added gender distribution cards for Male and Female customer counts.

- Step 15: Added branded title block containing PRISM INSURANCE PVT. LTD. for professional presentation.

- Step 16: Published the report to Power BI Service for sharing and collaboration.
 
![Publish_Message](https://github.com/user-attachments/assets/853ab0c4-40b7-45b5-b6d7-509b3d1460f4)

# Snapshot of Dashboard (Power BI Service)

![dashboard_snapo](https://github.com/user-attachments/assets/40e7570b-90fe-43cc-ac66-de09e5f75c42)

 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](https://github.com/user-attachments/assets/4fe8c9ff-eefb-4a1c-92ec-71ef032aa41d)

# Insights

A single-page interactive insurance dashboard was created, and the following insights can be derived:

### [1] Overall Financial Metrics

    Premium Amount: 5.98M

    Claim Amount: 16.91M
    
    Coverage Amount: 600.55M

    This shows that the total claim amount is significantly higher than premium income, indicating possible underwriting risks.           
### [2] Customer Metrics

    Gender Distribution
        - Female Customers: 5001
        - Male Customers: 5003
        Balanced gender distribution.
    
    Active vs Inactive Status
        - Active Customers: ~51%
        - Inactive Customers: ~49%
        Customer retention efforts may be required.
  
  
  ### [3] Premium Amount by Policy Type
  
      a) Travel : 2.5M
      b) Health : 1.2M
      c) Auto : 1.0M
      d) Life : 0.7M
      e) Home 0.6M
      Travel insurance is the highest contributor to premium revenue.

 ### [4] Claim Amount by Age Group
  
      Adults : 8.8M
      Elder : 6.4M
      Younger Adults: 1.7M
 
 ### [5] Claims by Status

      Rejected : 4.4k
      Settled : 3.4k
      Pending : 2.3k

      Rejected claims form the highest share, suggesting potential policy issues or documentation gaps.
 

