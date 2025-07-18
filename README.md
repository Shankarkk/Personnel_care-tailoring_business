🧵 Personal Care & Tailoring Business Insights

This project focuses on building a real-time analytics pipeline for a small-scale personal care (beauty parlour) and tailoring business. It captures services, appointments, and expenses, transforming raw service logs into a structured Snowflake data mart for business decision-making.


---

📌 Project Overview

Designed and implemented a mini data mart in Snowflake using dbt for a local tailoring and beauty services business.

Captured and transformed data for:

Customer appointments (hair, facial, stitching, etc.)

Service history and trends

Daily/weekly/monthly revenue analysis

Expense tracking and profitability




---

⚙️ Tech Stack

Snowflake – Cloud Data Warehouse

dbt (Data Build Tool) – Transformation logic (staging → mart)

Snowflake Tasks & Streams – For automation and change capture

Excel / Manual Logs – Raw data simulation (could be extended to S3/ADF)



---

✅ Key Features

Customer frequency tracking (weekly/monthly visit patterns)

Revenue by service category and stylist/tailor

Automated appointment ingestion using scheduled tasks

Expense vs Income trend for decision support



---

personnel_care_tailoring_business/
├── models/
│   ├── staging/              # Raw service and appointment data
│   ├── intermediate/         # Business logic layer (e.g., active customers, expenses)
│   ├── marts/                # Final reporting tables (service_summary, appointment_trends)
├── tests/                    # dbt test cases (not_null, unique)
├── snapshots/                # Snapshots if applicable
├── macros/                   # Custom dbt macros (optional)
├── dbt_project.yml           # Project configuration
├── packages.yml              # dbt dependencies
└── README.md                 # Documentation


---

📈 Business Impact

Enabled the business owner to track which services are most in-demand, peak customer hours, and daily revenue trends.

Helped monitor profit margins by comparing services rendered vs expenses incurred.

Provided insights for marketing and seasonal offers planning.


