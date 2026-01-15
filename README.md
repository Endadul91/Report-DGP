# 📊 Report-DGP – Excel to Defaulter Report Portal

This is a **free web-based portal** to upload an Excel file and automatically generate a **Defaulter Summary Report**.

The portal calculates:
- ✅ Total number of defaulters
- ✅ Total outstanding amount
- ✅ Total amount
- ✅ Displays full Excel data as a report table

---

## 🔧 Features
- Upload Excel file (.xls / .xlsx)
- Automatic calculation in browser
- No backend required
- Free hosting using GitHub Pages
- Instant report generation

---

## 📁 Expected Excel Format

The Excel file should contain the following columns (exact names):

- **Outstanding Amount**
- **Total Amount**

> Note: Column names are case-sensitive.

---

## 🧮 Calculations Logic

- **Total Defaulters**  
  → Count of rows where Outstanding Amount > 0

- **Total Outstanding Amount**  
  → Sum of Outstanding Amount

- **Total Amount**  
  → Sum of Total Amount

---

## 🚀 Live Portal
Access the portal here:  
🔗 https://endadul91.github.io/Report-DGP/

---

## 🛠️ Technologies Used
- HTML
- CSS
- JavaScript
- SheetJS (xlsx.js)
- GitHub Pages (Free Hosting)

---

## 📌 How to Use
1. Open the portal link
2. Upload Excel file
3. View summary and report instantly

---

## 📄 License
This project is free to use for educational and official reporting purposes.
