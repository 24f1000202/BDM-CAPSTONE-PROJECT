Financial Resilience Assessment & Risk Simulator

This project presents a data-driven financial risk assessment of a fleet-based commercial transport business with ₹9+ crore debt exposure. The objective was to evaluate debt sustainability, revenue concentration risk, and GST compliance integrity using quantitative analysis and scenario-based stress testing.

🔍 Problem Scope

The business faced:
High EMI obligations affecting liquidity
Heavy revenue concentration among top clients
GST mismatches and data integrity gaps

📊 Analytical Framework

The analysis integrates two structured datasets (fleet financing + sales/GST records) and implements:
Vehicle-level DSCR modeling under pessimistic, base, and optimistic revenue scenarios
Client concentration analysis using Pareto analysis, ABC classification, and Herfindahl–Hirschman Index (HHI)
GST anomaly detection using statistical deviation thresholds (±2 standard deviation rule)
Risk tier classification for decision-oriented intervention

🛠 Tech Stack

Python (pandas, numpy, matplotlib)
Statistical modeling
Data cleaning & preprocessing
React-based interactive dashboard

Deployed on Vercel

🌐 Interactive Prototype
An interactive financial stress simulator was built to allow scenario-based testing of:
Revenue contraction
EMI stress
Client loss impact
GST compliance risk
