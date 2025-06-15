
# 🏗️ Data Warehouse Project using SQL

This project demonstrates the design and implementation of a Data Warehouse system using SQL. It includes a robust star schema, data integration model, and multiple ETL flows. The project simulates a retail business scenario where transactional data is transformed into analytical insights.

---

## 📌 Project Objectives

- Design a scalable Data Warehouse architecture using the Star Schema.
- Model relationships using conceptual, logical, and physical schemas.
- Build fact and dimension tables optimized for analytics.
- Simulate ETL workflows with SQL inserts and transformation logic.
- Enable business insights through analytical SQL queries.

---

## 🗂️ Contents

- `DDL.sql` – Table creation scripts
- `ETL_scripts/` – SQL scripts to simulate data loads
- `diagrams/` – Data Flow, Data Model, and Integration SVG diagrams

---

## 🧱 Schema Design

The warehouse follows a **star schema** approach.

### 🌟 Fact Table
- **Fact_Sales** – Contains transactional data like quantity, revenue, and time references.

### 📐 Dimension Tables
- **Dim_Customer** – Customer profile information
- **Dim_Product** – Product categories and SKUs
- **Dim_Date** – Calendar and time metadata
- **Dim_Store** – Store locations and IDs

📊 These dimensions allow slicing and dicing sales metrics across multiple business angles.

---

## 🧩 Diagrams

| Diagram Type            | Preview |
|-------------------------|---------|
| Data Flow Diagram       | ![Data Flow]("D:\data_flow_diagram.drawio.svg") |
| Logical Data Model      | ![Data Model]("D:\data_model.drawio.svg") |
| Integration Architecture| ![Integration]("D:\integration_model.drawio.svg") |
|
---

## 🔄 ETL Simulation

The ETL scripts simulate:
- Ingestion of transactional data
- Transformation (e.g., data type casting, joins)
- Load operations into dimension and fact tables

SQL-based ETL flows were manually scripted to mimic real-world pipelines.

---

## 📈 Sample Business Insights

Sample queries included in `analytical_queries.sql` demonstrate how to:
- Get total sales by month and region
- Identify top-performing products
- Calculate customer retention or repeat purchase metrics
- Compare store-wise revenue trends

---

## 🛠️ Technologies Used

- SQL (PostgreSQL syntax)
- Draw.io for diagramming (saved as `.svg`)
- GitHub for version control and collaboration

---

## 📽️ Video Walkthrough

Check out the full explanation of architecture, schema, and data flow in this YouTube video:

▶️ [YouTube: Data Warehouse Project Demo](https://www.youtube.com/watch?v=9GVqKuTVANE)

---

## 📬 Contact

For any queries or suggestions:
- LinkedIn: [Amarnath Allamraju](https://www.linkedin.com/in/amarnathallamraju27/)
- GitHub: [Amarnath27me](https://github.com/Amarnath27me)

---

## 📄 License

This project is released under the MIT License. See `LICENSE` file for more details.


