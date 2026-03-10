 # 📊 PAA PND Dashboard — Power BI

> **Internship Project** | Pakistan Airports Authority (PAA)  
> Planning & Development (PND) Directorate

![Dashboard Preview]
<img width="1029" height="526" alt="image" src="https://github.com/user-attachments/assets/d96a4af5-95ed-49cf-997f-e2fa2aebaca9" />

---

## 📌 Overview

The **PND Dashboard** is an interactive Power BI report built for the Pakistan Airports Authority's Planning & Development Directorate. It provides executives and project managers with a real-time overview of development schemes, budget allocations, and project statuses across all PAA directorates.

---

## 🎯 Purpose

- Track **planning & development schemes** across PAA's 10 directorates
- Monitor **budget allocation vs. expenditure** per directorate
- Classify projects by **type, sector, and financial year**
- Enable data-driven decision-making for senior management

---

## 📷 Dashboard Preview

![PND Dashboard](dashboard_preview.png)

The dashboard includes:
- **KPI Cards** — Classification count, Total Types, Total Locations, Total Sectors, All Directorates
- **Directorate by Sector** — Donut chart (Public vs Corporate sector breakdown)
- **Directorate by Type** — Donut chart (On-going, New, ON-DEMAND, Completed, Disputed)
- **Sum of AllocationAmt by Directorate** — Bar chart showing budget allocations
- **ExpAmt by Directorate** — Bar chart for expenditure tracking
- **Estimated Cost by Directorate** — Bar chart for cost projections
- **Data Table** — Detailed scheme-level records with ADP codes, completion dates, and financial years

---

## 🏢 Directorates Covered

| # | Directorate |
|---|------------|
| 1 | CNS Engineering |
| 2 | Commercial Directorate |
| 3 | Engg: Services (Civil Works) |
| 4 | Engg: Services (E&M Works) |
| 5 | Flight Inspection |
| 6 | Information Technology (IT) |
| 7 | Logistic |
| 8 | Planning & Development |
| 9 | Rescue & Fire Fighting Services |
| 10 | Security Directorate |

---

## 🗂️ Project Classifications

- **Mega Schemes**
- **Regular Schemes**

**Financial Years Covered:** 2024-2025 · 2025-2026

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard development & visualizations |
| **Microsoft Excel / CSV** | Source data preparation |
| **DAX** | Calculated measures and KPIs |
| **Power Query (M)** | Data transformation and cleaning |
| **SQL Server / Excel** | Backend data source |

---

## 📁 File Structure

```
PAA-PND-Dashboard/
│
├── PND_Dashboard.pbix          # Main Power BI report file
├── data/
│   ├── schemes_data.xlsx       # Source data - scheme records
│   └── directorates.csv        # Directorate reference table
├── dashboard_preview.png       # Screenshot of the dashboard
└── README.md                   # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download)

### Steps to Run
1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/PAA-PND-Dashboard.git
   ```
2. **Open the report**  
   Open `PND_Dashboard.pbix` in Power BI Desktop

3. **Refresh data** *(if connecting to live source)*  
   Go to `Home → Refresh` and update data source credentials if prompted

4. **Explore the dashboard**  
   Use the slicers on the left panel to filter by:
   - Directorate
   - Financial Year
   - Classification

---

## 📊 Key Metrics Tracked

| Metric | Description |
|--------|-------------|
| **Classification** | Number of scheme classifications (5) |
| **Total Types** | Project types — On-going, New, etc. (2) |
| **Total Locations** | Geographic locations covered (28) |
| **Total Sectors** | Public & Corporate sectors (2) |
| **All Directorates** | Total PAA directorates included (10) |

---

## 💡 Key Insights Enabled

- Identify which directorates have the **highest budget allocation**
- Track **expenditure vs. allocation** gaps across departments
- Monitor **scheme completion progress** by financial year
- Filter and drill down on **individual ADP scheme codes**

---

## 👤 Author

laiba
Final Year Student | Computer Science  
Internship at: **Pakistan Airports Authority (PAA)**  
📧 laibaaslam383@gmail.com  
🔗 [LinkedIn]www.linkedin.com/in/laiba-a2834227b
🐙 [GitHub]https://github.com/laiba26-aslam

---

## 📄 License

This project was developed during an internship at Pakistan Airports Authority. All data is internal to PAA and has been anonymized/sanitized for portfolio use.

---
 
