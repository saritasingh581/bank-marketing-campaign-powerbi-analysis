📊 Bank Marketing Campaign Analysis | Power BI  

🚀 Project Overview  

This project analyzes a bank’s direct marketing campaign data to evaluate customer conversion patterns and campaign effectiveness using Power BI.  

The objective was to transform raw campaign data into business-ready insights that support smarter marketing decisions.  

🧠 Business Questions Answered  
- Which customer segments drive the highest subscription rates?  
- Does increasing campaign contacts improve or reduce conversion?  
- How does previous interaction impact future success?  
- What role do economic indicators (e.g., Euribor rate) play in customer decisions?  
- Is longer call duration actually improving outcomes?  

🔎 Approach  
1️⃣ Data Preparation (PostgreSQL)    
- Cleaned raw dataset  
- Handled missing values (e.g., pdays, categorical blanks)  
- Standardized columns and exported structured CSV  

2️⃣ Data Modeling (Power BI)  

- Verified data types  
- Created calculated columns  
- Built DAX measures for core KPIs  

3️⃣ KPI Development  

- Total Customers  
- Conversion Rate (%)  
- Subscribers per 100 Calls  
- Campaign Efficiency  
- Previous Contact Impact  
- Avg. Euribor Rate by Subscription  

4️⃣ Dashboard Design  

- Interactive slicers (Job, Housing, Loan)  
- Comparative conversion visuals  
- Campaign performance analysis  
- Economic influence tracking  

🛠 Tools Used
- Power BI  
- DAX  
- PostgreSQL  
- CSV Data Processing  

📂 Repository Structure  

'''
Bank-Marketing-PowerBI-Dashboard/
│
├── data/
│   ├── raw/
│   │   └── bank_marketing_raw.csv
│   └── processed/
│       └── bank_marketing_clean.csv
│
├── powerbi/
│   └── Bank_Marketing_Dashboard.pbix
│
├── screenshots/
│   └── dashboard_preview.png
│
└── README.md  
'''

📌 Key Takeaway  

This project demonstrates the complete analytics workflow:

Raw Data → SQL Cleaning → KPI Engineering → Business Dashboard → Actionable Insights

It reflects how marketing performance can be measured and optimized using data-driven decision-making.
