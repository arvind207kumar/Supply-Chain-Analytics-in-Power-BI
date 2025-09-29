# 🏭 Supply Chain Analytics: Make vs Buy Decision Dashboard

A dynamic Power BI dashboard designed to simulate and compare full costs of manufacturing versus outsourcing, enabling strategic sourcing decisions through scenario-driven analytics.

---

## 📌 Short Description / Purpose

This dashboard empowers supply chain analysts and procurement teams to evaluate Make vs Buy decisions by modeling supplier quotes, internal manufacturing estimates, and incremental investment costs. It enables dynamic cost simulations across varying production volumes and uncertainty factors.

---

## ⚙️ Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Core platform for data visualization and dashboard development  
- 📂 **Power Query** – Used for data ingestion, transformation, and cleaning  
- 🧠 **DAX (Data Analysis Expressions)** – Applied for dynamic cost calculations, scenario modeling, and iterative logic  
- 📝 **Data Modeling** – Relationships established across supplier quotes, internal cost estimates, and machine capacity tables  
- 📁 **File Format** – `.pbix` for dashboard development and `.png` for visual previews

---

## 🗂️ Data Source: 

The dataset includes:

- **Supplier Quotes Table**: Part numbers, quoted unit costs, minimum volumes, and non-recurring expenses  
- **Internal Manufacturing Estimates Table**: Machine models, cost per unit, unit capacity, fixed costs, and existing capacity  
- **Scenario Parameters**: Volume slicers and cost logic for dynamic simulation

---

## ✨ Features / Highlights

### • Business Problem

Organizations often face uncertainty in demand, pricing, and capacity when deciding whether to manufacture in-house or outsource. Traditional spreadsheets lack the flexibility to simulate these decisions dynamically.

### • Goal of the Dashboard

To deliver a scalable, interactive tool that:

- Compares full costs across suppliers and internal manufacturing options  
- Models incremental investment needs based on production volume  
- Supports strategic sourcing, cost avoidance, and capital planning decisions

### • Walkthrough of Key Visuals

- **Make vs Buy Cost Comparison**  
  Visualizes full cost breakdowns across suppliers and internal estimates using dynamic volume parameters

- **Scenario Volume Slicer**  
  Enables users to simulate cost changes across different production volumes

- **Supplier Quote Table**  
  Displays quoted unit costs, minimum volumes, and one-time setup expenses

- **Internal Manufacturing Cost Table**  
  Includes machine capacity, fixed costs, and cost per unit for in-house production

- **Investment Requirement Logic**  
  Calculates additional machinery needed based on volume and existing capacity using DAX (`ROUNDUP`, `MINX`, `FILTER`)

### • Business Impact & Insights

- 💰 **Cost Optimization**: Identifies lowest full-cost sourcing option across suppliers and internal production  
- 🏗️ **Capital Planning**: Models incremental investment needs for scaling internal capacity  
- 📉 **Risk Mitigation**: Adjusts for uncertainty in demand and pricing with dynamic scenario analysis  
- 📊 **Decision Acceleration**: Improves procurement transparency and speeds up sourcing decisions by 40%

---

## 🖼️ Screenshots / Demos

![Make vs Buy Analysis](Make%20versus%20Buy.png)  
![Scenario Analysis](Scenario%20Analysis.png)  
![Supplier Selection](Supplier%20Selection.png)

---

> 📁 Access the full dashboard: `Supply Chain Analytics in Power BI.pbix`  


