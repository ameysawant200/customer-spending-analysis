# 🛒 Customer Shopping Data Analysis

## 📊 Overview
This project performs an in-depth analysis of customer shopping behavior using a real-world transactional dataset. The goal is to clean, transform, and analyze the data to extract key marketing insights, uncover spending trends, and provide actionable business recommendations.

## 🛠️ Tools & Libraries Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Data Cleaning & Transformation
- Visualizations (histograms, boxplots, scatterplots)
- Outlier Detection & Log Transformation

## 📁 Dataset Summary
The dataset contains customer purchase information including:
- Customer ID, Age, Gender
- Product Category, Quantity, Price
- Payment Method, Shopping Mall, Invoice Date

## 📌 Key Steps
1. **Data Cleaning**:
   - Handled missing values (`price`, `payment_method`)
   - Removed outliers in `age` and `price`
   - Standardized column formats (e.g., converted invoice date to `datetime`)

2. **Exploratory Analysis**:
   - Histogram and boxplot visualizations of `age`, `price`, and `quantity`
   - Log transformation applied to `price` to handle skewed distribution

3. **Customer Segmentation**:
   - Spending by gender, age group, and product category
   - Identified high-value segments for marketing (e.g., females aged 26–55 purchasing clothing and shoes)

4. **Time Series Analysis**:
   - Monthly trend analysis of total spending
   - Pie chart of preferred payment methods

## 📈 Sample Visualizations
<img src="images/boxplot_price.png" width="400"/> <img src="images/spending_by_gender.png" width="400"/>

## 💡 Business Insights
- Clothing and Shoes categories generated the highest revenue
- Women aged 26–45 are the most lucrative customer group
- Credit card is the second most used payment method after cash
- Peak shopping occurs consistently across most months

## 🤖 Author
**Amey Pradeep Sawant**  
Master of Business Analytics, Macquarie University  
