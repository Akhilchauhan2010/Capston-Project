# 📊 E-Commerce Retail Analytics: Pricing & Inventory Strategy

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-Web%20Scraping-green)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-yellow?logo=scikitlearn)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-F2C811?logo=powerbi)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Overview
This capstone project focuses on analyzing e-commerce catalog data to uncover pricing patterns, inventory distribution, and revenue optimization opportunities.  

Using Python-based data analysis, machine learning, and Power BI dashboards, the project identifies pricing inefficiencies, stock risks, and opportunities for dynamic pricing strategies.

---

## 🎯 Objectives
- Scrape real-world product data using Python  
- Clean and preprocess raw datasets  
- Analyze pricing trends and inventory distribution  
- Identify stock risks and pricing anomalies  
- Build a machine learning model to predict product prices  
- Develop an interactive Power BI dashboard  

---

## 📂 Dataset
- **Source:** Web scraped data from books.toscrape.com  
- **Size:** 1,000 products across 50 pages  
- **Features:**
  - Book Title  
  - Price (GBP)  
  - Customer Rating (1–5 stars)  
  - Stock Quantity  

---

## ⚙️ Tech Stack
- **Language:** Python  
- **Libraries:**
  - BeautifulSoup (Web Scraping)  
  - Pandas, NumPy (Data Processing)  
  - Matplotlib, Seaborn (Visualization)  
  - Scikit-learn (Machine Learning)  
- **Tools:** Power BI  

---

## 🔄 Project Workflow

### 1️⃣ Web Scraping
- Scraped 1,000 product records from 50 pages  
- Extracted title, price, rating, and availability  

### 2️⃣ Data Cleaning & Feature Engineering
- Removed duplicates and missing values  
- Converted price and rating formats  
- Created new features:
  - Price Bands (Budget, Standard, Premium)  
  - Stock Status (Low vs Healthy)  
  - Rating Percentage  

### 3️⃣ Exploratory Data Analysis (EDA)
- Summary statistics (mean, median, spread)  
- Price vs rating trends  
- Stock distribution analysis  
- Correlation heatmap  

### 4️⃣ Model Building
- Model: **Random Forest Regressor**  
- Features:
  - Rating  
  - Stock Quantity  
- Metrics:
  - RMSE  
  - MAE  
  - R² Score  

### 5️⃣ Dashboard (Power BI)
- Interactive visualizations for:
  - Price distribution  
  - Stock health  
  - Model predictions  
- Filters for rating, price band, and inventory  

---

## 📊 Key Insights
- 📦 Inventory grouped into Budget, Standard, and Premium segments  
- ⚠️ Identified low-stock items prone to stockouts  
- 💡 Detected pricing inconsistencies and anomalies  
- 📈 Higher-rated products show pricing patterns  
- 🤖 ML model predicts optimal pricing based on features  

---

## 💡 Business Recommendations
- Monitor low-stock high-demand products  
- Adjust pricing for underpriced premium items  
- Use ML model for dynamic pricing decisions  
- Optimize slow-moving inventory with discounts  
- Use dashboards for real-time decision-making  

---

## 📸 Visualizations
<img width="549" height="362" alt="image" src="https://github.com/user-attachments/assets/d0a415ff-bdcb-4542-b8bb-57fe234fc6ce" />
<img width="787" height="581" alt="image" src="https://github.com/user-attachments/assets/8bdf29af-1abc-464c-9705-43222c7cab88" />
<img width="472" height="332" alt="image" src="https://github.com/user-attachments/assets/3b373c35-baf9-40d8-95c3-f665edc41cc4" />


---

## 🚀 How to Run

```bash
# Clone repository
git clone https://github.com/your-username/ecommerce-retail-analytics.git

# Navigate to project folder
cd ecommerce-retail-analytics

# Install dependencies
pip install -r requirements.txt

# Run script
python main.py
