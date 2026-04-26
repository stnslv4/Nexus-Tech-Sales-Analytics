# Nexus-Tech-Sales-Analytics
Interactive Power BI Dashboard for Sales and Profitability Analysis

### 🧠 Приклади використаних DAX-мір

Для розрахунку ключових показників було створено наступні міри:

**1. Чистий прибуток (Total Profit):**
TotalProfit = SUM('Orders'[Profit])

**2. Рівень маржинальності (Profit Margin):**
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)

**3. Темп росту продажів (Sales Growth %):**
Sales Growth % = DIVIDE([Total Sales] - [Sales Last Month], [Sales Last Month], 0)
