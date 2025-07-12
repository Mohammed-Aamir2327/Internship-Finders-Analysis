# 🎯 Internship Finder Data Analytics Project

This project aims to analyze internship trends using a simulated dataset that mimics real-world data from internship platforms. It is designed to help job-seeking students and career entrants make data-driven decisions using visual insights.

---

## 📌 Objective

To develop a data analytics solution that:
- Identifies in-demand internship roles and skills
- Highlights trends in stipend, mode, duration, and location
- Helps students plan applications more strategically
- Enables decision-making using dashboards and KPIs

---

## 🧠 Why Simulated Data?

We **did not use real data from LinkedIn or Internshala** due to:
- 🔐 **LinkedIn API restrictions and data privacy policies**
- 📵 **No legal access to scrape or use commercial datasets**
- ⚖️ To ensure ethical data usage and avoid violations

Instead, we generated a **realistic, large sample dataset** with fields commonly found in internship listings, such as: 
Fields: title, company, location, mode, duration, stipend, skills, deadline


---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Power BI** | Visual dashboard creation |
| **PostgreSQL** | Data querying and analysis |
| **Python (Optional)** | Data cleaning & generation (Jupyter Notebook) |

---

## 📂 Dataset Features

The simulated dataset contains:
- Internship titles like `Data Analyst Intern`, `AI/ML Intern`, `Graphic Design Intern`, etc.
- Modes: Online, Offline, Hybrid
- Stipend and Duration (1–6 months)
- Comma-separated skill tags (e.g., Python, Excel)
- Random future application deadlines
- 2000+ records for realistic volume

---

## 📊 Dashboard Overview (Power BI)

### ✅ **KPI Cards**
- `Upcoming Deadlines`
- `Total Count of Internships`
- `Number of Online Internships`
- `Average Stipend`

> Help users quickly understand the internship landscape.

---

### 📌 **Page 1 Visuals & Insights**

| Chart | Description | Recommendation |
|-------|-------------|----------------|
| **Internship Count by Domain** | Shows most common internship types (Finance, Data Analyst, AI/ML, etc.) | Focus on top-demand roles |
| **Mode of Internship (Donut)** | Visualizes online, offline, and hybrid mode shares | Prefer flexible modes; employers should consider hybrid |
| **Stipend Trends by Domain (Line Chart)** | Avg stipend across domains | Choose better-paying domains |

---

### 🌍 **Page 2 Visuals & Insights**

| Chart | Description | Recommendation |
|-------|-------------|----------------|
| **Location-wise Distribution (Map)** | Internship counts by city | Target top cities like Mumbai, Pune, Delhi |
| **Internship Duration (Donut Chart)** | Popular duration periods | 1–3 month roles dominate; plan availability |
| **Most In-Demand Skills (Bar Chart)** | Frequency of skills listed in postings | Learn Excel, Python, SQL, Tally, etc. |

---

## 🧩 SQL Queries (PostgreSQL)

Queries were written to:
- Count internships per domain
- Calculate average stipend
- Extract and rank in-demand skills
- Filter upcoming deadlines
- Analyze by mode and location

> All insights were built on real SQL queries — not hardcoded in Power BI.

---

## 📈 Key Learnings

- Created a full-stack data analytics pipeline: from data design to business insights.
- Learned to simulate real-world datasets ethically.
- Understood how to use KPIs, line graphs, donut charts, and maps for decision-making.

---

## 📢 How to Use

1. Clone the repository
2. Open Power BI and load `internship_data_large.csv`
3. Explore insights or customize dashboard visuals

---

## 💡 Final Note

This project is ideal for:
- Students preparing portfolios
- Aspiring data analysts
- Data visualization practice
- Resume & LinkedIn projects

**📣 Built with passion to solve a real problem through data.**

---





