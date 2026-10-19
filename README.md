# 📊 Google Sheets Dynamic Operations Dashboard

An interactive business intelligence application engineered in Google Sheets to convert flat transactional tracking records into dynamic, real-time operational insights for stakeholders.

## 🔗 Project Entry Points
*   **[🚀 Launch Interactive Live Dashboard (Creates Your Own Copy)](REPLACE_WITH_YOUR_MAKE_A_COPY_URL)**
*   **[📥 Download Static Workbook File (.xlsx)](./operations_dashboard_workbook.xlsx)**

---

## 🎨 Dashboard Preview
![Dashboard Preview](./images/dashboard_preview.png)
*(Note: Turn off sheet gridlines via View > Show > Gridlines before taking your screenshot to maintain this software-like interface).*

---

## 🏗️ Project Architecture

To protect raw transactional records while ensuring complete analytical accuracy, I designed a structured, three-tier spreadsheet data pipeline (**Data** → **Calculations** → **Presentation**) that strictly isolates back-end source fields from front-end interactive assets.

```text
[ Data Tier: Raw_Data ] ──(VLOOKUP / Logic)──> [ Logic Tier: Calculations ] ──(Pivot / Slicers)──> [ Presentation Tier: Dashboard ]
```

To standardize fragmented source fields, I engineered an intermediate logical mapping sequence across the dataset. Utilizing text manipulation functions alongside **relational lookup formulas (`VLOOKUP`)**, the data pipeline automatically matches operational keys, standardizes irregular strings, and groups dates into uniform temporal blocks without modifying the immutable master ledger.

To compress thousands of multi-variable tracking rows into high-level strategic intelligence, I architected a dedicated compute layer driven by **multi-dimensional Pivot Tables** and conditional aggregations (`SUMIFS`, `COUNTIFS`). By shifting intense math arrays away from the interface tab, the engine calculates regional performance metrics, calculates averages, and generates single-cell trend indicators (**`SPARKLINE` arrays**) simultaneously.

In the final layer of the architecture, I built a point-and-click user interface customized for executive decision-making. By explicitly binding **physical Data Slicers** and dropdown validation nodes directly to the underlying calculation matrices, the dashboard shifts from a static table to a responsive data application, allowing non-technical stakeholders to isolate metrics across multiple business channels instantly.

---

## 🛠️ Technical Competencies Demonstrated

*   **Data Architecture:** Multi-tier separation of concerns, data normalization, and integrity preservation.
*   **Advanced Spreadsheet Logic:** `VLOOKUP`, nested logical formulas (`IF`, `AND`), data validation boundaries, and conditional styling.
*   **Data Aggregation:** Multi-variable Pivot Tables, chronological trend line grouping, and conditional calculations (`SUMIFS`, `COUNTIFS`).
*   **Business Intelligence & UX:** Data Slicers, interactive dropdown arrays, dynamic chart execution, and grid-free visual layout design.

---

## 📂 Layer Schema Mapping

| Sheet Tab / Layer | Technical Component | Architectural Purpose |
| :--- | :--- | :--- |
| **`💵 Raw_Data`** | Primary Transaction Ledger | Secure storage of unaltered historical records. |
| **`⚙️ Calculations`** | `VLOOKUP` & Nested Logic | Relational cross-sheet mapping and string standardizations. |
| **`⚙️ Calculations`** | Pivot Matrices & `SUMIFS` | High-performance aggregation by timeline and category attributes. |
| **`⚙️ Calculations`** | `=SPARKLINE()` Formulas | Low-footprint, inline visual matrix generation for macro trends. |
| **`📊 Dashboard`** | KPI Scorecards & Core Charts | Front-end visual interface arranged for high-level scannability. |
| **`📊 Dashboard`** | Interactive Slicers & Dropdowns | Global point-and-click data filtration layers for stakeholders. |

---

## 📈 Key Takeaways

1.  **Zero-Maintenance Data Pipelines:** Established automated lookup points that update reporting layouts instantly when new historical rows are added to the system.
2.  **Self-Service Business Intelligence:** Shifted analytical friction away from tech teams by introducing interactive widgets, allowing non-technical users to run cross-functional queries independently.
3.  **Low-Overhead Solution Engineering:** Proved that robust, enterprise-ready data tools can be built utilizing open-access, zero-cost tools like Google Sheets without relying on immediate external software licenses.
