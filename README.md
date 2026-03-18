# ☕ Coffee Shop Sales Analysis

An end-to-end sales data analysis project on a New York City coffee shop chain. This project explores **6 months of transactional data** (Jan–Jun 2023) across 3 store locations to uncover revenue trends, peak hours, top-selling products, and store-wise performance — using Excel, with a built-in Dashboard and Analytics sheet.

---

## 📁 Project Structure

```
coffee-shop-sales-analysis/
│
├── COFFEE_SHOP_SALES.xlsx        # Full project file (data + analysis + dashboard)
└── README.md                     # Project documentation
```

### Sheets Inside the Excel File

| Sheet Name                  | Description                                         |
|-----------------------------|-----------------------------------------------------|
| `coffee-shop-sales-revenue` | Raw transactional data (149,116 records)            |
| `Analysics`                 | Pivot-based summary metrics and KPI calculations    |
| `DASHBOARD`                 | Visual dashboard with charts and slicers            |

---

## DashBoard
<img width="1027" height="632" alt="image" src="https://github.com/user-attachments/assets/62493093-4050-444b-ae65-796c04e4e27d" />

![COFFEE SHOP SALES xlsx - Analysics_page-0001](https://github.com/user-attachments/assets/3729590a-f277-4ff8-9fd4-34b66c9524d5)


## 🗃️ Dataset Overview

**Records:** 149,116 transactions  
**Period:** January 2023 – June 2023  
**Locations:** 3 stores across New York City

| Column               | Description                                          |
|----------------------|------------------------------------------------------|
| transaction_id       | Unique transaction identifier                        |
| transaction_date     | Date of purchase                                     |
| transaction_time     | Time of purchase                                     |
| transaction_qty      | Number of items purchased                            |
| store_id             | Store identifier                                     |
| store_location       | Store name / area                                    |
| product_id           | Product identifier                                   |
| unit_price           | Price per unit (USD)                                 |
| product_category     | High-level category (Coffee, Tea, Bakery, etc.)      |
| product_type         | Sub-category (Latte, Espresso, Scone, etc.)          |
| product_detail       | Full product name and size                           |
| Day                  | Day of month                                         |
| Month Name           | Month name                                           |
| Multiplication       | Revenue = unit_price × transaction_qty               |
| Hours                | Hour of transaction (0–23)                           |
| Day Name             | Day of week                                          |

---

## 📊 Key Metrics (Jan – Jun 2023)

| Metric                  | Value          |
|-------------------------|----------------|
| 💰 Total Revenue         | $698,812.33    |
| 🧾 Total Transactions    | 149,116        |
| 💵 Avg Bill / Person     | $4.69          |
| 📦 Avg Order Size        | 1.44 items     |
| 🏪 Number of Stores      | 3              |
| 🗓️ Period Covered        | 6 months       |

---

## 🔍 Analysis Highlights

### 📈 Monthly Revenue Trend

| Month    | Revenue      |
|----------|--------------|
| January  | $81,677.74   |
| February | $76,145.19   |
| March    | $98,834.68   |
| April    | $118,941.08  |
| May      | $156,727.76  |
| June     | $166,485.88  |

> 📌 Revenue grew **~2x from Jan to June**, showing a strong upward trend through the first half of 2023.

---

### 🏪 Store-Wise Revenue

| Store Location  | Revenue      |
|-----------------|--------------|
| Hell's Kitchen  | $236,511.17  |
| Astoria         | $232,243.91  |
| Lower Manhattan | $230,057.25  |

> All 3 stores perform closely, with Hell's Kitchen leading slightly.

---

### ☕ Top Product Categories by Revenue

| Category            | Revenue      |
|---------------------|--------------|
| Coffee              | $269,952.45  |
| Tea                 | $196,405.95  |
| Bakery              | $82,315.64   |
| Drinking Chocolate  | $72,416.00   |
| Coffee Beans        | $40,085.25   |

---

### 🏆 Top 5 Products by Revenue

| Product                         | Revenue     |
|---------------------------------|-------------|
| Sustainably Grown Organic Lg    | $21,151.75  |
| Dark Chocolate Lg               | $21,006.00  |
| Latte Rg                        | $19,112.25  |
| Cappuccino Lg                   | $17,641.75  |
| Morning Sunrise Chai Lg         | $17,384.00  |

---

### ⏰ Peak Hours

| Hour  | Transactions |
|-------|--------------|
| 10 AM | 18,545       |
| 9 AM  | 17,764       |
| 8 AM  | 17,654       |
| 7 AM  | 13,428       |
| 11 AM | 9,766        |

> ☀️ Morning hours (7–10 AM) are the busiest — typical coffee shop rush pattern.

---

### 📅 Revenue by Day of Week

| Day       | Revenue      |
|-----------|--------------|
| Monday    | $101,677.28  |
| Friday    | $101,373.00  |
| Thursday  | $100,767.78  |
| Wednesday | $100,313.54  |
| Tuesday   | $99,455.94   |
| Sunday    | $98,330.31   |
| Saturday  | $96,894.48   |

> Weekdays generate slightly more revenue than weekends, with Monday being the top day.

---

## 🛠️ Tools Used

| Tool            | Purpose                                      |
|-----------------|----------------------------------------------|
| Microsoft Excel | Data storage, pivot analysis, dashboard      |
| Pivot Tables    | Aggregation and KPI summaries                |
| Excel Charts    | Visual representation of trends              |
| Slicers         | Interactive filters on the Dashboard         |

---

## 💡 Key Findings

- Revenue shows a **consistent upward growth** of ~104% from January to June 2023.
- **Coffee dominates** with 38.6% of total revenue, followed by Tea at 28.1%.
- All 3 NYC stores have **near-equal performance**, suggesting consistent operations.
- **Morning (8–10 AM)** is the peak window — ideal for staffing and stock planning.
- **Weekdays outperform weekends** slightly, suggesting a strong commuter/office customer base.
- **Large-size premium products** (Organic Coffee Lg, Dark Chocolate Lg) are top revenue drivers.

---

## 🙋‍♂️ Author

**Parth**  
🔗 [GitHub](https://github.com/parth-visualize)

---
