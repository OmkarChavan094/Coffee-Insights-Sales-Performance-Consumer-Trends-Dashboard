# ☕ Coffee-Insights: Sales Performance & Consumer Trends Dashboard

An end-to-end business intelligence and data analysis project analyzing transactional coffee sales data to uncover purchasing behaviors, revenue drivers, time-of-day peaks, and payment preferences.

---

## 📌 Project Overview

The **Coffee-Insights** project provides a comprehensive overview of retail coffee sales performance across multiple dimensions, including temporal patterns (hourly, weekday, monthly), payment behaviors, and daypart demand. The interactive dashboard enables cafe operators and stakeholders to monitor revenue trends, optimize staffing, and refine sales strategies.

---

## 📊 Dashboard Preview

![Coffee-Insights Dashboard](dashboard_screenshot.png)

### Key Metrics Tracked
* **Total Cups Sold:** High-volume transaction tracking across all beverage categories.
* **Total Sales & Revenue:** Gross sales tracking with growth rate benchmarks.
* **Average Order Value (AOV):** Measure of spend per transaction.
* **Total Orders:** Volume analysis over operational periods.

---

## 🔍 Key Insights & Findings

* **Peak Seasonal Demand:** Revenue spikes prominently during transitional quarters (March and October), highlighting optimal windows for seasonal menu promotions.
* **Daypart Contribution:** Sales peak during the **Afternoon** and **Morning** windows, identifying prime operating hours for labor scheduling and inventory prep.
* **Payment Preference:** Cash transactions account for the majority share (~53.7%), followed by online payments (~31.6%) and card transactions (~14.7%).
* **Weekday Distribution:** Peak ordering volumes consistently cluster during weekdays (notably Tuesday and Monday afternoons).

---

## 📁 Dataset Details

The underlying dataset (`Coffe_sales.xlsx`) consists of over 3,500 transactional records with the following attributes:

| Column | Description |
| :--- | :--- |
| `Date` & `Time` | Timestamp of the transaction |
| `hour_of_day` | Hour bucket (6:00 to 22:00) |
| `Time_of_Day` | Operational window (*Morning*, *Afternoon*, *Night*) |
| `Weekday` | Day of the week (*Mon* – *Sun*) |
| `Month_name` | Calendar month of transaction |
| `coffee_name` | Product item (*Latte*, *Americano*, *Cappuccino*, etc.) |
| `money` | Transaction amount / price |
| `cash_type` | Payment method (*cash*, *card*, *Online*) |

---

## 🛠️ Tech Stack & Tools

* **Data Cleaning & Modeling:** Microsoft Excel / Power Query
* **Visualization & BI:** Microsoft Power BI 
* **Analytics & Exploration:** Python (pandas)

---

## 🚀 How to Use / Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/coffee-insights-analysis.git](https://github.com/your-username/coffee-insights-analysis.git)
   cd coffee-insights-analysis
