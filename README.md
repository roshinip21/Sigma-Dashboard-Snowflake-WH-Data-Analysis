

# 📊 Sigma Dashboard – Snowflake Warehouse Compute, Storage & Query Analytics

This project showcases a **set of interactive dashboards built in Sigma Computing**, designed to analyze and visualize **Snowflake warehouse usage, query performance, compute costs, and storage trends**. The dashboards utilize data from core Snowflake tables like `WAREHOUSE_EVENTS_HISTORY`, `WAREHOUSE_METERING_HISTORY`, `QUERY_HISTORY`, and `DATABASE_STORAGE_USAGE_HISTORY`.

## 🔍 Purpose

The dashboards provide a **comprehensive overview of Snowflake operational metrics**, allowing engineering, finance, and product teams to monitor cost drivers, track query performance, and optimize compute resources.

---

## 📁 Dashboards Created

### 1. **Warehouse Events History**

* Pivot table showing manual vs auto warehouse start/stop/resume events.
* User activity breakdown by `USER_NAME`, `EVENT_NAME`, and timestamp.
* KPI cards to track event frequency.

### 2. **Warehouse Compute Cost Dashboard**

* Line chart for weekly or monthly cost trends.
* Pie chart of cost contribution by warehouse.
* Filtered insights by warehouse size and type (Standard/X-Small/etc).

### 3. **Storage Usage Analysis**

* Visual breakdown of **database-level storage usage** (per GB).
* Monthly trend chart for tracking storage growth.
* Warehouse-wise stacked bar chart.

### 4. **Query Cost & Performance**

* Interactive pivot table with `QUERY_TEXT`, `EXECUTION_TIME`, `WAREHOUSE_NAME`, and `TOTAL_ELAPSED_TIME`.
* Query types and execution time comparison via bar charts.
* Top expensive queries & slow-running jobs.

---

## 🧩 Features Used

* **UI Containers & Tabs** for organized layout.
* **Interactive Filters**: Date range, warehouse name, query type.
* **Custom KPIs**: Execution Time, Total Cost, Avg Query Time.
* **Visuals**: Line chart, Pie chart, Bar chart, Pivot tables.
* **Responsive Layout** using Sigma’s no-code design tools.

---

## 🛠️ Tools & Technologies

| Tool             | Purpose                                |
| ---------------- | -------------------------------------- |
| **Sigma BI**     | Interactive BI tool for Snowflake      |
| **Snowflake**    | Source of analytical warehouse data    |
| **SQL**          | Used in Sigma’s queries and transforms |
| **Pivot tables** | For user-warehouse event tracking      |

---

## 📌 Business Use Case

> The dashboards help engineering and business teams **identify high-cost queries**, **track warehouse utilization**, and **optimize resource allocation**. This leads to **cost reduction**, **performance improvements**, and **better visibility** into Snowflake operations.

---

## 📷 Sample Screenshots

> *(Add screenshot markdown links below once hosted on GitHub)*

```markdown
![Warehouse Events](images/warehouse-events.png)

```

---

## 📈 Future Enhancements

* Add scheduling alerts for cost spikes or inactive warehouses.
* Integrate usage forecasting using ML.
* Export capability for offline business reviews.


