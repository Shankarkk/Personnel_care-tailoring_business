💄🧵 **Personal Care Business Analytics** (`personalcare-analytics`)

A real-world data project designed to **track and analyze** customer visits, service usage, and tailoring orders for a **small-scale personal care business**, combining beauty parlour and tailoring services. Powered by **Snowflake**, **dbt**, and **CI/CD automation** for clean, testable analytics.

---

## 🔧 **Tech Stack**

- **Snowflake** – Central data warehouse (staging → intermediate → mart)
- **dbt Cloud** – ELT modeling with Jinja + built-in tests
- **GitHub** – Versioning and CI/CD integration
- **SQL + dbt Tests** – Business rules and validation
- *(Optional: GSheets, CSV or ADF for data load)*

---

## 🧩 **Key Features**

- 💇 **Service analytics** for beauty parlour (facial, hair spa, bridal packages, etc.)  
- 🧵 **Tailoring service tracking** (orders, delivery time, type of stitch)  
- 🧍 **Customer frequency and category insights**  
- ✅ **Tested models** with dbt `unique`, `not_null`, `accepted_values`  
- 🔁 **Incremental models** for growing data (daily/weekly visits)

---

## 📁 **Project Structure**

```bash
personalcare-analytics/
├── models/
│   ├── staging/             # Raw input (appointments, services, tailoring)
│   ├── intermediate/        # Calculated visits, service counts, time logic
│   └── marts/               # Final metrics: customer ranking, popular services
├── tests/                   # dbt schema + data quality checks
├── macros/                  # Jinja for date logic or categorization (optional)
├── dbt_project.yml          # Core dbt config
├── packages.yml             # dbt dependencies
└── README.md                # Documentation


---

📊 Business Impact

🔍 Understood which services generate more income

⏱️ Tracked turnaround time for tailoring orders

📅 Identified peak customer days/times

🧠 Enabled better service combos based on usage patterns

📈 Increased repeat customer visits through frequency insights



---

👤 Author

Shankar Kamalakannan
Freelance Snowflake + dbt Developer

📱 Mobile: +91-95976 45086
📧 Email: shankar.freelance.dataengineer@gmail.com
🔗 GitHub: https://github.com/shankarkk

---
