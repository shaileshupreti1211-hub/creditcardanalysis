1. Project Overview

The Credit Card Analysis Project focuses on analyzing customer credit card usage, transactions, and payment behaviors using a relational database system. The goal is to provide insights into customer spending habits, payment patterns, and credit utilization, which are crucial for banks and financial institutions to reduce risk, detect fraud, and improve customer relationship management.

The project uses a structured ER database model and SQL queries to extract insights. It is supported by business documentation (.docx), a visual ER diagram (.jpg), SQL implementation (.sql), and a presentation (.pptx).

2. Objectives

To design a relational database for managing credit card transactions and customer details.

To analyze customer spending patterns across different categories.

To study payment behaviors (full vs. minimum due payments).

To evaluate credit utilization and repayment risks.

To generate reports and dashboards for decision-making.

3. Data Description

The database schema (from the ER diagram & SQL script) includes:

Customer Table: Stores customer details (ID, Name, Age, Gender, Income, etc.).

Credit Card Table: Card number, type (Visa, MasterCard, etc.), limit, issue/expiry dates.

Transaction Table: Transaction ID, Date, Amount, Merchant, Category.

Payment Table: Payment ID, Date, Amount Paid, Due Amount, Status (on-time/late).

Bank Table: Issuing bank details, branch, region.

4. Methodology
   
✅ Database Design

Entity-Relationship (ER) model created to design database structure.

Normalized to reduce redundancy and improve query efficiency.

✅ SQL Queries & Analysis

Queries for customer spending behavior (highest spenders, top merchants).

Queries for credit utilization (average card usage vs. credit limit).

Repayment behavior (late payments, minimum due trends).

Fraud detection queries (unusually high transactions, abnormal usage patterns).

✅ Reporting & Presentation

Results summarized into dashboards (PowerPoint presentation).

Use cases presented for business decision-making (loyalty programs, credit risk monitoring, fraud detection).

5. Tools & Technologies Used

Database: MySQL / SQL Server (implemented via .sql file).

Visualization: Power BI / Tableau (for dashboards, if linked).

Documentation: Microsoft Word (project report).

Presentation: Microsoft PowerPoint (project summary).

6. Key Insights & Findings

Spending Patterns: Customers spend more on retail, dining, and travel categories.

Repayment Trends: A large portion of users pay only the minimum due, indicating potential credit risk.

Credit Utilization: Customers with higher utilization are more likely to default on payments.

Fraud Detection: SQL queries can flag suspicious transactions (e.g., multiple high-value spends in a short time).

Customer Segmentation: High-value customers identified for rewards programs.

7. Applications

Banking Sector: Monitor repayment risks and improve credit risk models.

Fraud Detection: Real-time monitoring of unusual spending behavior.

Customer Relationship Management (CRM): Target high-value customers with loyalty programs.

Financial Planning: Helps banks optimize card limits and offers based on usage trends.

8. Conclusion

The Credit Card Analysis Project demonstrates how database systems and SQL-based analytics can uncover valuable insights into customer behavior. By analyzing transactions, repayments, and spending habits, financial institutions can reduce risk, detect fraud, and enhance customer satisfaction. This project integrates database design (ER model), data analysis (SQL queries), and business reporting (Word/PPT) to deliver a holistic analytical solution.
