# 📊 Sales Data Analysis Project

This project involves analyzing sales data using Python to gain meaningful business insights. The notebook covers data cleaning, exploration, visualization, and key metric generation to identify trends and performance patterns.

---

## 🧰 Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **Pandas** for data manipulation
- **Matplotlib & Seaborn** for data visualization
- **NumPy** for numerical operations
- **OS & Glob** for file management

---

## 📂 Dataset

The project works with **monthly sales data** stored in multiple CSV files. These datasets contain:
- Order IDs
- Product names
- Purchase addresses
- Quantities
- Prices

The data is merged into a single DataFrame for comprehensive analysis.

---

## 📈 Key Features

- 🔗 **Combining Monthly Reports**  
  Automated merging of multiple CSV files into one dataset for analysis.

- 🧼 **Data Cleaning**  
  - Handling NaN values
  - Removing duplicates
  - Parsing and converting columns into appropriate formats (e.g., `Date`, `Quantity Ordered`, `Price Each`)

- 📊 **Sales Trend Analysis**  
  - Best months for sales
  - Top-selling cities
  - Most popular products

- 📦 **Product Mix Analysis**  
  - Product-wise quantity vs. price insights
  - Correlation between product price and quantity sold

- 🛍️ **Frequently Sold Together Items**  
  Identifies products often bought together using `groupby` and `combinations`.

---

## 🔍 Insights Derived

- **Peak sales months** for marketing focus
- **Best-performing cities** for logistics and expansion
- **Products often sold together** — ideal for bundle offers
- **Relationship between price and quantity sold** — useful for pricing strategy

---

## ▶️ How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/your-username/sales-data-analysis.git
   cd sales-data-analysis

