# 📊 Task 15: Customer Segmentation (RFM Analysis)

## 🔎 Project Overview
This project performs Customer Segmentation using RFM (Recency, Frequency, Monetary) Analysis on an E-Commerce dataset (Online Retail).

RFM helps businesses identify high-value customers and create targeted marketing strategies.

---

## 📁 Dataset Information
Dataset: Online Retail II  
Columns Used:
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

---

## 📌 Steps Performed

### 1️⃣ Data Cleaning
- Removed cancelled invoices
- Removed null CustomerID values
- Converted InvoiceDate to datetime format
- Created TotalPrice column (Quantity × UnitPrice)

### 2️⃣ RFM Calculation
- Recency → Days since last purchase
- Frequency → Number of unique invoices
- Monetary → Total spending amount

### 3️⃣ RFM Scoring
- Used quantile binning (qcut)
- Created R, F, M scores (1–5 scale)
- Combined into RFM Score

### 4️⃣ Customer Segmentation
Customers classified into:
- Champions
- Loyal Customers
- At Risk
- Regular Customers

### 5️⃣ Visualization
Bar chart showing number of customers in each segment.

### 6️⃣ Export
Generated:
- `rfm_segments.csv`

---

## 📈 Business Impact
RFM segmentation helps:
- Improve customer retention
- Increase revenue through targeted campaigns
- Reduce churn
- Personalize marketing strategies

---

## 📦 Deliverables
- task15_rfm.ipynb
- rfm_segments.csv
- segment_actions.txt
- README.md

---

## 🎯 Final Outcome
Successfully segmented customers based on purchasing behavior and provided actionable business strategies.
