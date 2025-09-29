# 📦 Metadata – Supply Chain Analytics in Power BI

## 🧩 Product Dimensions

| Column      | Description                                                                 |
|-------------|-----------------------------------------------------------------------------|
| Part_Number | Identification number for the product or component                          |
| Part_Name   | Name of the product or component                                             |
| Project     | Name of the project the product/component is associated with                |

---

## 🏭 Internal Manufacturing Estimates Table

| Column                        | Description                                                                                   |
|-------------------------------|-----------------------------------------------------------------------------------------------|
| Machine_Model                 | Model of manufacturing equipment                                                              |
| Part_Number                   | ID of the product/component being cost-estimated                                              |
| Cost_per_Unit                 | Marginal production cost per unit (includes material, labor, variable overheads)              |
| Unit_Capacity                 | Number of units the machine can produce when fully utilized                                   |
| Machine_Fixed_Cost           | One-time cost of acquiring a new machine                                                      |
| Existing_Capacity             | Available capacity of current machinery                                                       |
| Machine_Fixed_Overhead_Rate  | Non-scalable cost of owning/operating the equipment                                           |

---

## 📑 Quotes Table

| Column               | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| Supplier             | Name of the supplier providing the quote                                    |
| Part_Number          | ID of the product/component being quoted                                    |
| Volume               | Minimum order volume required for quoted cost                               |
| Quoted_Cost          | Cost per unit quoted by the supplier                                        |
| Non_recurring_expenses | One-time cost to enable production at the quoted volume                    |

---

> 📌 This metadata supports dynamic scenario modeling and cost comparison logic in Power BI dashboards for Make vs Buy decisions.
