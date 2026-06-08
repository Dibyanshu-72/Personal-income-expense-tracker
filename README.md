<div align="center">

# 💰 Personal Income & Expense Tracker

### *A clean, formula-driven Excel spreadsheet to take control of your finances*

[![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)]()
[![Made with ❤️](https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge)]()

<br/>

> **Track income. Control spending. Hit your savings target — every month.**

<br/>

---

</div>

## 📸 Preview

| Section | Highlights |
|---|---|
| 🟢 **Income Panel** | Job · Freelance · Rental — auto YTD |
| 🔴 **Expense Panel** | 9 categories with emoji labels |
| 💚 **Net Savings Row** | Live formula: Income − Expenses |
| 🎯 **vs Target Row** | Gap vs ₹60,000 monthly goal |

---

## ✨ Features

- **📊 Live Formulas** — 39 auto-calculated cells; just fill in your numbers
- **📅 6-Month View** — Jan through Jun with Year-to-Date auto-sum
- **🎯 Savings Target** — Built-in ₹60,000/month benchmark row
- **🎨 Color-Coded Design** — Green = income, Red = expenses, teal = totals
- **🔒 Zero Formula Errors** — Verified clean with no `#REF!`, `#DIV/0!` or `#VALUE!`
- **📱 Print Ready** — Frozen header panes, clean layout

---

## 🚀 Getting Started

### 1. Download
```bash
git https://github.com/Dibyanshu-72/Personal-income-expense-tracker
```

Or just click **`Code → Download ZIP`** above.

### 2. Open in Excel
```
📂 Open: Personal_Income_Expenses_Beautified.xlsx
```
> Works with **Microsoft Excel 2016+**, **Google Sheets**, and **LibreOffice Calc**

### 3. Fill in your data
- Blue cells = **your inputs** (Jan–Jun for each category)
- All totals, YTD, and savings rows calculate **automatically**

---

## 📁 File Structure

```
📦 personal-income-expense-tracker/
 ┣ 📊 Personal_Income_Expenses_Beautified.xlsx   ← Main tracker
 ┗ 📄 README.md                                  ← You are here
```

---

## 📋 Spreadsheet Layout

```
┌─────────────────────────────────────────────────────────────┐
│        💰  Personal Income & Expense Tracker                
│        📌  Monthly Savings Target :  ₹ 60,000               
├──────────────┬──────┬──────┬──────┬──────┬──────┬──────┬────┤
│  Category    │ Jan  │ Feb  │ Mar  │ Apr  │ May  │ Jun  │YTD │
├──────────────┴──────┴──────┴──────┴──────┴──────┴──────┴────┤
│                         INCOME                              │
│  💼 Job        🔵    🔵    🔵   ...  ...  ...   ⚫        
│  💻 Freelance  🔵    🔵    🔵   ...  ...  ...   ⚫        
│  🏠 Rental     🔵    🔵    🔵   ...  ...  ...   ⚫        
│  ✅ Total      ⚫    ⚫    ⚫    ⚫   ⚫   ⚫    ⚫     | 
├─────────────────────────────────────────────────────────────┤
│                        EXPENSES                             │
│  🛒 Groceries  🔵    🔵    🔵   ...  ...  ...   ⚫       
│  👗 Clothing   🔵    🔵    🔵   ...  ...  ...   ⚫       
│  🍔 Junk Food  🔵    🔵    🔵   ...  ...  ...   ⚫       
│  ... (6 more categories)                                    │
│  ❌ Total      ⚫    ⚫    ⚫    ⚫   ⚫   ⚫    ⚫     │
├─────────────────────────────────────────────────────────────┤
│  💰 Net Savings ⚫   ⚫    ⚫    ⚫   ⚫   ⚫    ⚫     │
│  🎯 vs Target   ⚫   ⚫    ⚫    ⚫   ⚫   ⚫    ——      
└─────────────────────────────────────────────────────────────┘
  🔵 = Hardcoded input     ⚫ = Auto-calculated formula
```

---

## 💡 How to Customize

| Want to... | How |
|---|---|
| Change savings target | Edit cell value in the red title bar |
| Add a new income source | Insert a row inside the Income section |
| Add a new expense | Insert a row inside the Expenses section |
| Change currency | Find & Replace `₹` with your symbol |
| Extend to 12 months | Add Jul–Dec columns and extend SUM ranges |

---

## 📊 Sample Data (Jan–Mar)

| | Jan | Feb | Mar | YTD |
|---|---|---|---|---|
| **Total Income** | ₹1,30,000 | ₹1,35,000 | ₹1,20,000 | ₹3,85,000 |
| **Total Expenses** | ₹32,950 | ₹79,000 | ₹29,700 | ₹1,41,650 |
| **Net Savings** | ₹97,050 | ₹56,000 | ₹90,300 | ₹2,43,350 |
| **vs ₹60K Target** | ✅ +₹37,050 | ✅ -₹4,000 | ✅ +₹30,300 | — |

---

## 🛠️ Built With

- **Microsoft Excel** — Workbook engine & formula calculation
- **openpyxl** — Python library used to generate & format the file
- **Calibri** — Clean, professional font throughout

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- 🐛 Report bugs via [Issues](../../issues)
- 💡 Suggest new expense categories
- 🌍 Add multi-currency support
- 📈 Add chart/visualization sheets

```bash
# Fork → Clone → Create branch → Commit → Pull Request
git checkout -b feature/add-charts
```


<div align="center">

**Made with ❤️ for better personal finance habits**

*If this helped you, please ⭐ star the repo!*

[![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/personal-income-expense-tracker?style=social)](../../stargazers)

</div>
