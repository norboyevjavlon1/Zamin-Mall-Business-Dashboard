# Zamin-Mall-Business-Dashboard
Zamin Malls - Commercial Real Estate BI Dashboard

Overview
This project is an end-to-end Business Intelligence solution developed for Zamin Malls Group, a commercial real estate operator managing over 96,000 sqm of leasable area across four major shopping centres. The dashboard transitions raw leasing, footfall, and financial data into actionable executive insights, shifting the focus from simple data tracking to proactive yield maximization and risk management.

The Business Problem
The executive team needed to move beyond basic revenue reports to understand the true drivers of mall profitability. Key challenges included:

Differentiating between "Asking Rate" and "Actual Collected Rate" per SQM.

Evaluating tenant health using Occupancy Cost Ratios (OCR) and Sales Density.

Identifying "at-risk" revenue through early lease terminations and high-arrear tenants.

Validating the reliability of self-reported tenant turnover against POS-integrated data.

Data & Tech Stack

Database: SQL (10+ relational tables including dim_lease, fact_lease_month, fact_tenant_sales)

BI Tool: Microsoft Power BI

Data Modeling: Star Schema (1 Fact table related to multiple Dimension tables)

Language: DAX (Complex measures for time-intelligence, area-based occupancy, and financial KPIs)

Key DAX Implementations

Area-Based Occupancy: Calculated occupancy precisely by square meters (SQM) rather than simple unit counts to reflect true asset utilization.

Sales Density & OCR: Developed measures to track tenant financial health and risk of default.

Expiring Leases SQM: Forward-looking 12-month area expiry logic to assist the leasing team in pipeline management.

Dashboard Structure

Executive Overview: High-level KPIs (Total Collected Revenue, Collection Rate, YoY Growth) with mall-by-mall share analysis.

Space & Rate: Matrix breakdowns of Actual Rate per SQM by floor and zone, highlighting premium and underperforming areas.

Tenants & Turnover: Deep dive into tenant performance (Top/Bottom 10), Occupancy Cost Ratios, and Arrears tracking.

Leasing & Footfall: Risk analysis focusing on early terminations by leasing agents, rent-free months distributed, and footfall-to-spend conversions.

Key Business Insights Delivered

Tenant Mix Strategy: Declining "Spend per Visitor" in specific branches signals a need for immediate tenant mix restructuring.

Data Integrity: Discrepancies between POS-integrated tenants and manual-declaration tenants revealed hidden turnover, leading to a recommendation for mandatory POS integration in future leases.

Vacancy Risk: A strong correlation was found between specific leasing agents and early lease terminations, identifying a direct cause of unexpected vacancy costs.
