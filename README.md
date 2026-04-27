Telecom Customer Churn Analysis:
An end-to-end exploratory data analysis and machine learning project on a telecom customer dataset (~7,000 records), aimed at identifying the key drivers behind customer churn and translating findings into business recommendations.

Objective:
Understand why customers leave and when they're most at risk, using data segmentation, visualization, and predictive modeling — framed as a business problem, not just a technical exercise.

 Dataset:
Telco Customer Churn dataset with 33 features including:

Customer demographics (gender, senior citizen status)
Account info (tenure, contract type, payment method)
Services subscribed (streaming, internet, phone)
Financials (monthly charges, total charges)
Target variable: Churn Label / Churn Value


Tools & Libraries:
Python( Core language)
Pandas(Data loading & manipulation)
Matplotlib / Seaborn(Visualizations)
Scikit-learn(ML model & feature importance)
Google Colab(Runtime environment)

 Analysis Highlights:
1. Churn by Tenure
Customers were segmented into three cohorts — 0–12 months, 1–2 years, and 2+ years — to examine how churn rate evolves over time.
Key finding: Newer customers (0–12m) churn at significantly higher rates, while long-tenured customers show strong brand loyalty. This points to the first year as the critical retention window.
2. Predictive Modeling (Random Forest)
Features used: Total Charges, Senior Citizen, Streaming Movies
Model Accuracy: 67.71%
Top Feature:Total Charges (96.0% importance)
Secondary FeatureSenior Citizen (2.6%)
Tertiary FeatureStreaming Movies (1.5%)

 Business Recommendations:
1. Pricing is the #1 churn driver — Total Charges dominates feature importance. The brand should audit pricing tiers and consider optimized plans for price-sensitive segments.
2. The 0–12 month window is highest risk — early intervention strategies (onboarding offers, loyalty incentives) could significantly reduce churn.
3. Age as a secondary signal — Senior customers behave differently; age-targeted retention programs may improve outcomes for that segment.

👤 Author
Maansi BR — Business & AIML
LinkedIn · GitHub
