# Deloitte Virtual Internship - Task 02

## 🕵️‍♂️ Task: Forensic Analysis of Gender Pay Equality

This repository contains my solution for **Task 02** of the **Deloitte Technology Consulting Virtual Internship** on Forage.

---

## 📝 Task Overview

Daikibo Industrials raised internal concerns about **gender inequality in salary distribution**. The **Forensic Tech team** processed employee compensation data and provided an `Equality Table.xlsx` that quantifies **gender pay equality** using a score between **-100 and +100** for each job role across different factories.

---

## 🎯 Objective

- **Input:**  
  A spreadsheet with the following columns:
  - `Factory`  
  - `Job Role`  
  - `Equality Score` (integer from -100 to +100)

- **Output:**  
  Add a **new column**: `Equality Class` based on the following rules:

| Equality Score Range | Classification        |
|----------------------|-----------------------|
| Between -10 and +10  | Fair                  |
| < -10 or > 10        | Unfair                |
| < -20 or > 20        | Highly Discriminative |

**Examples:**
- `10` → Fair  
- `-9` → Unfair  
- `30` → Highly Discriminative

---

## 📂 Files in this Task
   - Equality_table.xlsx
   

