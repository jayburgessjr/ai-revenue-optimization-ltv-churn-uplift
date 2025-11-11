# AI-Driven Revenue Optimization: LTV, Churn & Uplift (End-to-End)

This project is a production-style example of how I use AI/ML to drive revenue decisions instead of vanity metrics.

It simulates a realistic customer funnel (acquisition → engagement → offers → revenue) and walks through:

- Synthetic but business-shaped data for marketing, product usage, and revenue.
- A **churn model** to identify at-risk customers worth saving.
- An **LTV model** to rank customers by long-term value.
- A simple **uplift modeling** approach to decide **who should receive offers** for maximum incremental impact.
- Proper evaluation: ROC-AUC, RMSE, calibration-style checks, feature importance, and policy simulation.

Everything is structured the way I’d approach this in a Lakehouse + Databricks environment:
clear assumptions, explainable features, and outputs that map directly to retention, targeting, and growth levers.
