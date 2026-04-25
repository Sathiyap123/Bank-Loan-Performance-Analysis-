📊 Bank Loan Performance Analysis Dashboard

🧾 Executive Summary / Purpose

This project presents an interactive Power BI dashboard designed to analyze bank loan data and evaluate lending performance.
It helps identify key trends in loan approvals, borrower behavior,
and default risks, enabling financial institutions to make informed, data-driven decisions.

The dashboard focuses on improving loan portfolio health by tracking performance metrics and highlighting high-risk segments.

📌 Key Features & KPIs

💰 Total Loan Applications

💵 Total Funded Amount & Amount Received

📉 Default Rate (Bad Loans %)

📈 Good Loan vs Bad Loan Analysis

👥 Borrower Segmentation (Income, Employment Length)

📊 Loan Status (Fully Paid, Current, Charged Off)

📅 Monthly & Yearly Loan Trends

🌍 Regional Loan Distribution

➡️ These KPIs help monitor lending performance, risk levels, and profitability.

🛠 Technical Stack

Power BI Desktop – Dashboard creation
Power Query (M) – Data transformation
DAX – Calculated measures & KPIs
Excel / CSV Dataset – Data source
🗄 Data Source & Modeling

Data Source: Loan dataset (CSV / Excel format)

Data Cleaning:

Removed missing values
Standardized formats
Handled inconsistencies

Data Model:

⭐ Implemented Star Schema
Fact Table: Loan Data

Dimension Tables:

Borrower Details
Time (Date)
Location

This structure improves performance and enables better analysis.

⚙️ Installation / Setup Instructions

Download the Repository

git clone https://github.com/Sathiyap123/Bank-Loan-Performance-Analysis-.git
Open in Power BI
Open .pbix file using Power BI Desktop
Update Data Source (if required)

Go to: Transform Data → Data Source Settings
Update file path
Refresh Dashboard
Click Refresh to load data

📈 Insights Generated

Majority of loans fall under good loan category, but a portion still contributes to risk
Employment length and income significantly impact loan repayment
Certain regions contribute more to loan volume
Loan purpose affects default probability

➡️ Similar analyses show that loan data helps identify risk patterns and improve lending strategies.

🔮 Future Enhancements

🔹 Add real-time data integration (SQL / API)
🔹 Build loan default prediction model (ML)
🔹 Deploy dashboard to Power BI Service
🔹 Add drill-through and advanced filters

✅ Conclusion

This project demonstrates how data visualization tools like Power BI can transform raw banking data into meaningful insights.
By analyzing loan performance, borrower profiles, and risk indicators,
the dashboard supports better decision-making and enhances financial strategy.
