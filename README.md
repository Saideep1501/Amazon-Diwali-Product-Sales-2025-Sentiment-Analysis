# 🪔 Amazon Diwali Product Sales 2025 – Sentiment Analysis

## 🎯 Project Overview
This project analyzes Amazon Diwali 2025 sales data, focusing on **product performance, customer reviews, and sentiment trends**.  
The goal is to uncover actionable business insights to understand customer satisfaction and revenue patterns during the festive season.

> **Note:** The dataset used is **synthetic**, designed to simulate realistic Amazon sales data for learning and demonstration purposes.

---

## 📊 Dataset

The dataset contains the following columns:

| Column | Description |
|--------|-------------|
| `Order_ID` | Unique identifier for each order |
| `Date` | Date of purchase |
| `Customer_ID` | Unique customer identifier |
| `Product_Category` | Category of the product |
| `Product_Name` | Name of the product |
| `Quantity` | Number of items purchased |
| `Unit_Price_INR` | Price per unit (INR) |
| `Total_Sales_INR` | Total revenue per order (INR) |
| `Payment_Method` | Payment method used |
| `Delivery_Status` | Delivered, Returned, or Pending |
| `Review_Rating` | Customer review rating (1–5) |
| `Review_Text` | Customer review text |
| `State` | Customer location – state |
| `Country` | Customer location – country |

---

## 🧰 Tools & Libraries
- Python 
- Jupyter Notebook  
- `pandas`, `numpy` – Data manipulation  
- `matplotlib`, `seaborn` – Data visualization  
- `TextBlob` – Sentiment analysis  
- `datetime` – Date/time transformation  

---

## 🔄 Workflow

1. **Data Import & Cleaning**
   - Imported CSV dataset using `pandas`.
   - Cleaned column names, converted dates, and added derived columns like `Month`, `Week`, and `Day`.

2. **Exploratory Data Analysis (EDA)**
   - Analyzed total sales, total orders, and average order value.
   - Identified top-selling products and categories.
   - Visualized payment method preferences and delivery status.

3. **Sentiment Analysis**
   - Generated sentiment scores from review text using `TextBlob`.
   - Categorized reviews as **Positive**, **Neutral**, or **Negative**.
   - Visualized sentiment distribution and linked sentiment to revenue and product categories.

4. **Insights Generation**
   - Evaluated revenue contribution by sentiment.
   - Analyzed top-selling products vs average sentiment.
   - Identified product categories with highest revenue and best customer perception.
   - Explored actionable insights to improve product performance and customer satisfaction.

5. **Visualization**
   - Bar plots, scatter plots, and boxplots to highlight key trends.
   - Revenue and sentiment distributions visualized for business-friendly interpretation.

---

## 💡 Key Business Insights

- **Revenue & Orders:** ₹1.12 billion from 15,000 orders; avg. order value ₹74,544; avg. quantity 3.  
- **Customer Sentiment:** Only 49.4% of reviews were positive; the rest were neutral or negative.  
- **Revenue by Sentiment:** Positive reviews contributed 49.19% of total revenue, negative 27.42%.  
- **Category-Level Insights:** Beauty products led in revenue; Electronics topped sentiment rankings.  
- **Top Products by Quantity Sold:** Perfume, Children’s Books, Headphones, Lipstick, Hair Dryers. None of these rank in top 5 by sentiment, highlighting improvement opportunities.  
- **Actionable Insight:** Promote high-sentiment, lower-selling products and improve quality for high-volume, low-sentiment items.

---

## 💡 Learnings & Takeaways

- Gained hands-on experience performing **sentiment analysis on e-commerce data**, from text preprocessing to deriving actionable insights.
- Learned how customer sentiments **impact revenue, product perception, and business decision-making** during festive sales campaigns.
- Developed the ability to connect **qualitative feedback (reviews) with quantitative metrics (sales, revenue, order volume)** to identify opportunities for product improvement and targeted marketing.
- Strengthened skills in **EDA, data visualization, and business storytelling**, making insights accessible to non-technical stakeholders.

---

## 📢 Connect With Me

- [LinkedIn](https://www.linkedin.com/in/saideepvemunuri/)
- [Portfolio](https://codebasics.io/portfolio/Saideep-Vemunuri)
- [Email](vemunurisaideep1501@gmail.com)

---
