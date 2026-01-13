# Airbnb-Data-Warehouse-QlikView-Dashboard
This project extends an Airbnb transactional database into a data warehouse–ready model and a QlikView dashboard. The main objective was to transform a normalized relational schema into a fact–dimension (star) schema, eliminate synthetic keys and loops, and create a semantic layer suitable for business intelligence and analytics.


# 🛠 Tools & Technologies

**QlikView · MySQL · SQL · Data Warehousing · Dimensional Modeling · ETL · BI Dashboards**



## 🔹 What I Did in This Project

### 🔸 1. Data Model Transformation

* Took the original Airbnb relational schema
* Redesigned it into a **fact and dimension model**
* Identified:

  * **Fact tables** (Bookings, Reviews)
  * **Dimension tables** (Guest, Host, Property, Date)

---

### 🔸 2. Removed Loops & Synthetic Keys

* Renamed fields and adjusted relationships
* Eliminated circular references and loops
* Ensured a **clean star-schema structure**


---

### 🔸 3. QlikView Data Load Script

* Loaded data from the source tables
* Applied transformations and field standardization
* Built associations aligned with dimensional modeling rules

---

### 🔸 4. QlikView Dashboard Development

* Designed interactive dashboards for:

  * Bookings analysis
  * Host and guest activity
  * Property performance
* Implemented filters, KPIs, and visual charts
* Ensured business-friendly reporting

---

## 🔹 Learning Objectives Achieved

* Understood the difference between **OLTP vs OLAP**
* Applied **dimensional modeling concepts**
* Learned how to:

  * Break loops in BI tools
  * Build a semantic layer
  * Design dashboards for decision-making
* Gained hands-on experience with **QlikView**





