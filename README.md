# risk-finance-dashboard
 
Bank of America: Risk & Finance Dashboard

- Interactive dashboard that retrieves risk and finance feed and sign off data from various databases and APIs

- Learning Objectives: develop a dashboard that consolidates risk and finance data
    - Specifications (modules):
        1) Main Dashboard: consoludate all modules, database and CSV connection checking
        2) Feed Status Dashboard: retrieve LOB - report CSV mapping, check LOB - report feed status, check book level granularity, check MRS feed information, email corresponding LOB parties based on CSV mapping, command line execution
        3) Signoff Status Dashboard: check aggregated LOB - nodes outstanding signoff, check LOB - nodes - business unit outstanding signoff
        4) Feed-Report Dependency: map tabular feed-report from CSV file, edit and refresh CSV
        5) Report-Batch Dependency: map tabular and tree strucutre report-batch, retrieve metadata from tree structure to allow hadnling of errors, edit and refresh CSV
- Python Libraries: Quartz UI, QzTable, mysql.connector
- Improvements: implement trigger report-batch functions based on output metadata
