# Project Overview

The "HOTEL REVENUE MANAGEMENT" project transforms raw hospitality data into actionable insights. It moves beyond standard reporting to provide a predictive and strategic analytics system. The solution empowers General Managers and Revenue Managers to optimize pricing, segment customers based on behavior, and mitigate revenue leakage through forecasting.

# Tech Stack

- Tool: Microsoft Power BI Desktop, Excel
- Data Transformation: Power Query (ETL)
- Data Modeling: Star Schema (Fact & Dimension Tables)
- Language: DAX (Data Analysis Expressions)
- Visualization: Interactive Dashboards, What-If Parameters, Custom Tooltips

# Key Features & Modules

1. Data Foundation & Operational Metrics
   * Star Schema Architecture: Designed a robust data model linking Bookings (Fact) with Customers, Rooms, Branches and Dates (Dimensions).
   * Granular KPIs: Calculated daily performance metrics including ADR (Average Daily Rate), RevPAR (Revenue Per Available Room), and Occupancy % to establish a single source of truth.

2. Guest Segmentation & RFM Analysis
   * Behavioral Clustering: Implemented RFM (Recency, Frequency, Monetary) analysis using DAX to classify guests into strategic clusters: High Spenders, Loyal Guests, and First-Timers.
   * Demographic Insights: Analyzed booking patterns to reveal that Solo Travelers drive volume, while Family/Corporate guests drive duration..

3. Forecasting & Risk Management
   * Churn Prediction: Analyzed Lead Time and Cancellation Trends to identify high-risk booking windows.
   * Demand Forecasting: Utilized time-series forecasting to predict future occupancy, aiding in staff and inventory planning.

4. Revenue Strategy & Dynamic Pricing
   * Dynamic Pricing Engine: Built an interactive What-If Scenario Tool using DAX parameters. This allows managers to simulate price changes (Price Uplift) and market reaction (Occupancy Sensitivity) to find the optimal RevPAR sweet spot.
   * Ancillary Revenue: Analyzed non-room revenue streams (Spa, Dining) to identify upsell opportunities.

5. Role-Specific Dashboards
   * General Manager (GM) View: High-level executive summary focusing on branch benchmarking and overall profitability.
   * Revenue Manager (RM) View: Tactical dashboard for managing pricing tiers, cancellation policies, and customer retention.

# Impact

This solution empowers the hotel management team to:
- Eliminate Guesswork: Replace intuition-based pricing with data-backed simulations.
- Target Marketing: Shift marketing spend toward high-value segments identified through RFM analysis.
- Proactive Operations: Anticipate demand drops and cancellations before they impact the bottom line.
