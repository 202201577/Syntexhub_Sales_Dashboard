# 📊 Syntexhub Sales Dashboard

## 📋 Project Overview
A comprehensive analysis of Superstore sales data spanning 4 years (2014-2017), uncovering key business insights and trends to support data-driven decision making. This project includes both Python-based analysis and an interactive dashboard built with Google Data Studio.

## 🛠️ Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Google Colab** (Development Environment)
- **Google Data Studio** (Interactive Dashboard)
- **Google Sheets** (Data Source)
- **Kaggle** (Dataset Source: Sample Superstore)

## 📊 Key Metrics

| Metric | Value |
|--------|-------|
| 💰 Total Revenue | $2,297,200.86 |
| 📈 Total Profit | $286,397.02 |
| 📊 Profit Margin | 12.47% |
| 🧾 Total Orders | 5,009 |
| 👥 Total Customers | 793 |
| 📦 Total Products | 1,862 |

## 🎯 Key Insights

### 🏆 Top Performing Products
- **Best Seller:** Canon imageCLASS 2200 Advanced Copier ($61,599)
- **Lowest Performer:** Eureka Disposable Bags ($1.62)

### 🌍 Regional Performance
| Region | Sales | Profit |
|--------|-------|--------|
| West | $725,457.82 | $108,418.45 |
| East | $678,781.24 | $91,522.78 |
| Central | $501,239.89 | $39,706.36 |
| South | $391,721.90 | $46,749.43 |

### 📦 Category Performance
| Category | Sales | Profit |
|----------|-------|--------|
| Technology | $836,154.03 | $145,454.95 |
| Furniture | $741,999.80 | $18,451.27 |
| Office Supplies | $719,047.03 | $122,490.80 |

### 📈 Yearly Growth Trend
- 2014: $484,247.50
- 2015: $470,532.51
- 2016: $609,205.60
- **2017: $733,215.26** ⬆️

## 📊 Interactive Dashboard

🔗 **Live Dashboard:** [View on Google Data Studio](https://lookerstudio.google.com/reporting/a983f3d8-7697-4221-8d66-a8d41450a0c7/view)

![Dashboard Preview](dashboard_screenshot.png)

### Dashboard Features:
- **4 KPI Cards** — Revenue, Profit, Orders, Customers
- **Yearly Sales Trend** — Bar chart (2014-2017)
- **Sales by Region** — Bar chart (West, East, Central, South)
- **Sales by Category** — Bar chart (Technology, Furniture, Office Supplies)
- **Monthly Sales Trend** — Time series analysis
- **Theme:** Constellation (Dark professional theme)

## 🔍 Analysis Steps
1. **Data Cleaning** — Removed nulls, duplicates, converted date formats
2. **Feature Engineering** — Extracted Year, Month, Quarter, YearMonth
3. **KPI Calculation** — Revenue, Profit, Profit Margin
4. **Trend Analysis** — Monthly, Quarterly, Yearly sales patterns
5. **Product Analysis** — Top and low performing products
6. **Regional & Category Analysis** — Performance comparison
7. **Data Visualization** — Charts in Python + Interactive Dashboard in Data Studio

## 📁 Project Files
| File | Description |
|------|-------------|
| `Syntexhub_Sales_Dashboard.ipynb` | Complete Python analysis code |
| `superstore_cleaned.xlsx` | Cleaned dataset (Excel format) |
| `sales_analysis.png` | Python visualization charts |
| `dashboard_screenshot.png` | Interactive dashboard preview |
| `README.md` | Project documentation |

## 🚀 How to Run
1. Open `Syntexhub_Sales_Dashboard.ipynb` in Google Colab
2. Upload `superstore_cleaned.xlsx` to Colab
3. Run all cells sequentially
4. For the interactive dashboard, open the live link above

## 💡 Business Recommendations
- **Focus on Technology category** — highest profit margin
- **Improve Furniture profitability** — high sales but very low profit ($18K from $742K)
- **Expand in West region** — best performing market
- **Investigate low-performing products** — discontinue items below $10 in sales

## 🔗 Connect with Syntexhub
- 🌐 Website: [syntexhub.com](#)
- 💼 LinkedIn: [@Syntexhub](https://linkedin.com/company/syntexhub)
- 📸 Instagram: [@Syntexhub](#)

---
*This project was completed as part of the Syntexhub Virtual Internship Program (Data Analysis Track).*
