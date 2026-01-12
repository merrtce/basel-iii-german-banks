Analysis of Basel III capital ratios for Germany's 10 largest banks

Research Question: How significantly do Germany's top 10 banks exceed Basel-III minimum capital requirements?  
Data Source: European Banking Authority (EBA), 2025 EU-wide Transparency Exercise  
Scope: Germany - 10 largest banks  
Time Period: 2025 Q2  
Main Metrics: CET-1, Tier 1 and Leverage Ratios  
Tools: Microsoft Excel, SQL (MySQL), Tableau  

Project Objective

This analysis contains a comparative assessment of the capital adequacy ratios of
the ten largest banks in Germany under Basel III by using the European Banking
Authority (EBA) 2025 EU-wide Transparency Exercise dataset. The main objective of
this project is to provide insights into the financial robustness of these ten banks by
analyzing their compliance with Basel III adequacy criteria. This project covers the
ten largest banks in Germany, including Deutsche Bank, Commerzbank, and
NRW.Bank, on the basis of Q2 2025 data.

Methodology

1. Filtering a raw EBA CSV file which contains 90,000 records by using Microsoft
Excel based on German banks' LEI codes, time period, and country information.
2. Checking for missing or wrong datas and comparing CET-1, Tier 1 and leverage
ratios by using SQL.
3. Categorizing banks into risk groups (“Very Strong”
,
”Strong”
,
”Normal”) based on
their CET-1 ratios.
4. Visualizing findings as graphs and charts in Tableau.

Key Findings

- The average CET-1 ratio of the ten banks analyzed is 17.9%. This is nearly four
times higher than the minimum level of 4.5% required under Basel III.
- NRW.bank has the highest CET-1 ratio at 24.6%, while Deutsche Bank has the
lowest at 14.2%.
- 30% of banks are “very strong,
” 50% are “strong,
” and 20% are “normal."

Project Structure

basel-iii-german-banks/  
├──- sql/ # SQL queries for analysis  
├──- data/ # Sample dataset  
├──- tableau/ # Tableau visualisations  
├──- report/ # Analysis report in PDF format  
└──- README.md # Project documentation  

1. Review SQL queries in the /sql folder for analysis methodology
2. Open Tableau files in /tableau to explore tableau visualisations
3. Read the full analysis in /Project

License

This project is for portfolio and educational purposes. Data from the European Banking Authority (EBA) is used in accordance with transparency exercise guidelines.

Author

- Mert Cevher
- Master's Student in Public Economics, Law and Politics
- www.linkedin.com/in/mertcevher | mert.cevher@stud.leuphana.de
