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
  <img width="975" height="479" alt="image" src="https://github.com/user-attachments/assets/e7d8f497-c6e9-4023-b1b2-7c9e44d71d91" />



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
<img width="975" height="511" alt="image" src="https://github.com/user-attachments/assets/83a55879-8bc8-478c-ad83-0e40a5c32555" />
<img width="975" height="511" alt="image" src="https://github.com/user-attachments/assets/c6fb244e-6a72-46d0-9965-043bf38a747f" />
<img width="975" height="510" alt="image" src="https://github.com/user-attachments/assets/cb93c147-f98a-4aef-a104-7fa2739fbe66" />


<img width="975" height="515" alt="image" src="https://github.com/user-attachments/assets/392bb75d-cee3-4b94-882e-f28868e83275" />

---

## 🔹 Learning Objectives Achieved

* Understood the difference between **OLTP vs OLAP**
* Applied **dimensional modeling concepts**
* Learned how to:

  * Break loops in BI tools
  * Build a semantic layer
  * Design dashboards for decision-making
* Gained hands-on experience with **QlikView**





