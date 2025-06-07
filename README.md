# 📊 Blinkit Sales Dashboard - Power BI

This Power BI project provides a comprehensive analysis of Blinkit's sales data, helping uncover key trends, performance metrics, and business insights across various outlet types, item categories, and locations.

![Dashboard Preview](/blinkit.png) 

---

## 📌 Overview

This interactive dashboard visualizes multiple dimensions of the Blinkit dataset to help:
- Track total and average sales
- Understand customer preferences via average ratings
- Analyze sales by item type, outlet type, size, and location tier
- Monitor outlet establishment trends over time

---

## 📁 Dataset Description

This dataset contains transactional records from a retail store, combining item, outlet, and sales details. Below are the key fields in the dataset:

| Column Name                 | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| `Item Fat Content`         | Type of fat content in the item (e.g., Low Fat, Regular)                    |
| `Item Identifier`          | Unique ID of the item                                                       |
| `Item Type`                | Category/type of the item (e.g., Dairy, Frozen Foods, Household)            |
| `Outlet Establishment Year` | Year the outlet was established                                             |
| `Outlet Identifier`        | Unique ID of the outlet                                                     |
| `Outlet Location Type`     | Tier-based classification of outlet location (Tier 1, Tier 2, Tier 3)       |
| `Outlet Size`              | Size of the outlet (Small, Medium, High)                                    |
| `Outlet Type`              | Type of store (Supermarket Type1/2/3, Grocery Store)                        |
| `Item Visibility`          | Visibility percentage of the item in the store                              |
| `Item Weight`              | Weight of the item (in some standard unit)                                  |
| `Sales`                    | Sales value generated for the item                                          |
| `Rating`                   | Customer/Store rating associated with the item                              |

---

## 📈 Key Insights

- 🟢 **Total Sales**: `$444.79K`
- 🔵 **Average Sales**: `$142`
- 🟡 **Total Items**: `3,139`
- ⭐ **Average Rating**: `3.9 / 5`

### 📊 Visual Highlights

1. **Sales by Year (Outlet Establishment Trend)**  
   Peak around 2015–2016; significant drop by 2020.

2. **Sales by Outlet Size**  
   Medium-sized outlets outperform others.

3. **Sales by Tier Location**  
   Tier 2 and Tier 1 cities dominate; Tier 3 underperforms.

4. **Top Performing Item Categories**  
   - Fruits & Vegetables  
   - Snack Foods  
   - Household Items

5. **Fat Content Preference**  
   Customers prefer **Regular Fat** items over Low Fat.

6. **Outlet Type Comparison**  
   - **Supermarket Type 1** has higher sales  
   - **Grocery Stores** show better visibility and slightly higher average ratings

---

## 🛠️ Tools & Technologies Used

- **Power BI**: For interactive dashboard creation
- **Excel/CSV**: For raw data input
- **DAX**: For calculated fields and KPIs

---

## 📎 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/blinkit-powerbi-dashboard.git
   ```
2. Open `Blinkit_Dashboard.pbix` in Power BI Desktop.
3. Refresh data sources (if needed).
4. Use filters for **Outlet Location Type**, **Size**, and **Item Type** to explore insights.

---

## 🧠 Future Improvements

- Add profit/margin analysis
- Drill-down by month/quarter
- Highlight best/worst performing SKUs
- Incorporate customer segmentation

---

## 🌟 If you found this useful, feel free to star ⭐ the repo or share your feedback!
