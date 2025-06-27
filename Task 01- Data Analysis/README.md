# Deloitte Virtual Internship - Task 1

## 📊 Project Title: Daikibo Factory Telemetry Analysis

This repository contains my solution for **Task 1** of the **Deloitte Technology Consulting Virtual Internship** on Forage. The objective of this task was to analyze telemetry data from Daikibo's factories and answer two business-critical questions using Tableau.

---

## 📁 Task Overview

### ✅ Objective:
Analyze telemetry data collected from four Daikibo factory locations for the month of **May 2021**, and answer:

1. **In which location did machines break the most?**
2. **What are the machines that broke most often in that location?**

---

## 🏭 Factories Included:
- **Meiyo** – Tokyo, Japan 🇯🇵  
- **Seiko** – Osaka, Japan 🇯🇵  
- **Berlin** – Berlin, Germany 🇩🇪  
- **Shenzhen** – Shenzhen, China 🇨🇳  

Each factory had 9 types of machines, sending messages every 10 minutes.

---

## 🧰 Tools Used
- [Tableau Desktop (Free Trial)](https://www.tableau.com/products/desktop)
- JSON Dataset provided by Daikibo

---

## 🛠️ Steps Taken

1. **Imported JSON data** into Tableau.
2. Created a **calculated field** called `Unhealthy`:
   ```tableau
   IF [status] = "unhealthy" THEN 10 ELSE 0 END
---
