# cleaned_amazon_sales
# 📊 Amazon Product Analysis Dashboard (Power BI)

An interactive Power BI dashboard built using Amazon product listing data to analyze product performance across categories, pricing, discounts, and customer ratings.

---

## 🎯 Objective

To help business stakeholders explore and understand:
- Revenue trends
- Best-performing products
- Discount and rating patterns
- Category-wise product performance

---

## 🧰 Tools Used

- **Power BI Desktop** (Dashboard creation)
- **Python (Pandas)** (Data preprocessing)
- **Microsoft Excel** (Optional column adjustments)

---

## 📁 Dataset

- File: `amazon_cleaned.csv`
- Columns include: `ProductName`, `DiscountedPrice`, `ActualPrice`, `Rating`, `RatingCount`, `DiscountPercent`, `MainCategory`, and more.
- Estimated **Total Revenue** was calculated as:  
  `DiscountedPrice × RatingCount`

---

## 📐 Dashboard Layout
The link to the dashboard:-https://app.powerbi.com/groups/me/dashboards/2ab49326-d354-4ca8-9bfb-d3ee9a26a1c2?ctid=54fc4ca8-44ea-4dd1-a1ee-8d18a8571f81&pbi_source=linkShare

### 🔹 **Page 1: Executive Summary**
- KPI Cards: Total Revenue, Avg Rating, Avg Price, Review Count
- Bar Chart: Top 10 Products by Revenue
- Slicers: Category, Price, Rating

---

### 🔹 **Page 2: Category Insights**
- Column Chart: Revenue by MainCategory
- Slicers: Category Filter

---

### 🔹 **Page 3: Product Details**
- Detailed Table: ProductName, Prices, Ratings, Discounts, Revenue
- Scatter Plot: Discount vs Rating (Bubble size = Reviews)
- Slicers: ProductName, Rating, Price, Discount

---

## 📌 Key Insights

- Products with **higher discounts** often had **mixed ratings**.
- **Top revenue** came from select categories like *Laptops* and *Accessories*.
- Some **highly rated products** had **lower visibility** due to less discounting.

---

## 🚀 How to Use

1. Open `amazon_cleaned.csv` in Power BI
2. Apply calculated columns (e.g., `TotalRevenue`)
3. Use slicers and visuals to interactively explore the dataset
4. Navigate across report pages for deep analysis

---

## 📎 Deliverables

- ✅ Power BI `.pbix` file (dashboard)
- ✅ Cleaned dataset (`amazon_cleaned.csv`)
- ✅ This README

---

## 📧 Contact

Created by **Shaik Adnan**  
Feel free to reach out on GitHub or LinkedIn for feedback or suggestions.

