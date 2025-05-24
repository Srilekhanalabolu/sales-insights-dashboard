# sales-insights-dashboard
This project presents an interactive Tableau dashboard built to analyze and visualize sales performance across various dimensions. The goal is to uncover key insights from historical sales data to support data-driven business decisions.
# Sales Insights Dashboard

This repository contains a Tableau dashboard project designed to provide insightful analysis of sales data. The dashboard visualizes key sales metrics, regional performance, product trends, and time-based patterns to help business users make data-driven decisions.

---

## 📊 Dashboard Preview

Two preview images of the dashboard are available (exported as PowerPoint slides):

- `sales.pptx`
- `sales insight.pptx`

*You can view these for a quick visual summary of the dashboard design.*

---

## 🗂 Project Files

| File Name           | Description                                         |
|---------------------|-----------------------------------------------------|
| `salesinsights.twbx`| Tableau packaged workbook containing the dashboard  |
| `db_dump.sql`       | Raw MySQL database dump file with sales data        |
| `sales.pptx`        | Dashboard export image in PowerPoint format         |
| `sales insight.pptx`| Additional dashboard export image in PowerPoint     |

---

## 💾 Data Source

- The sales data is sourced from the MySQL dump (`db_dump.sql`).
- Data processing and queries were done using SQL Workbench before connecting to Tableau.
- The Tableau workbook uses this data to build interactive sales insights.

---

## 🛠 Tools Used

- **Tableau Desktop** — for dashboard development and visualization.
- **SQL Workbench** — for managing and querying the MySQL dump.
- **MySQL** — database system for sales data.
- **GitHub** — for project hosting and version control.

---

## 🔗 Usage Instructions

1. Import the MySQL dump file `db_dump.sql` into your MySQL server.
2. Open the Tableau workbook `salesinsights.twbx` in Tableau Desktop.
3. Update the data source connection in Tableau to point to your MySQL server and database.
4. Explore and interact with the sales dashboard.
5. Preview the dashboard layout by viewing the PowerPoint files (`sales.pptx`, `sales insight.pptx`).

---

## 📌 Notes

- Ensure your MySQL user uses the `mysql_native_password` authentication plugin for compatibility with Tableau.
- Download and install the latest MySQL connector/driver recommended by Tableau here:  
  https://www.tableau.com/support/drivers
- The PowerPoint files provide a handy visual reference for the dashboard's appearance.

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

*Created by srilekha nalabolu*  

