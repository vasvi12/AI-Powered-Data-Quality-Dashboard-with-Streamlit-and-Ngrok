# AI-Powered-Data-Quality-Dashboard-with-Streamlit-and-Ngrok
This project provides a complete pipeline for analyzing the quality of a sales dataset using Python. It includes both a command-line and an interactive web-based dashboard powered by Streamlit and deployed via Ngrok, making it accessible from anywhere. The dashboard evaluates missing data, validates formats (like emails and phone numbers).
# 📊 AI-Powered Data Quality Dashboard

An interactive dashboard built using **Streamlit** and **Ngrok** that helps visualize, validate, and monitor the quality of tabular datasets — specifically tailored around a sales dataset.

---

## 🚀 Features

- ✅ **Dataset Overview** (Rows, Columns)
- 🔎 **Missing Value Detection**
  - Tabular Summary
  - Bar Charts
  - Heatmaps
  - Pie Charts
- 🔁 **Duplicate Records Detection**
- 📧 **Validation of Email and Phone Number Formats**
- 💰 **Sales Amount Analysis**
  - Descriptive Statistics
  - Histograms and Boxplots
  - Daily and Monthly Trend Visualization
- 🔄 **Detection of Significant Changes in Sales (±20%)**
- 🧮 **Correlation Analysis for Numeric Columns**
- 🔟 **Top Frequent Categorical Values**
- 📦 **Top Customers by Total Sales**
- 📅 **Time Series Trends: Daily and Monthly**

---

## 📁 Dataset

The dataset used is `ai_data_quality_dataset.csv`, assumed to contain fields like:

- `customer_id`
- `order_date`
- `sales_amount`
- `email`
- `phone_number`
- And other categorical/numerical fields

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Seaborn / Matplotlib
- Streamlit
- Ngrok

---

## 📦 Installation & Usage

### 🔧 Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/data-quality-dashboard.git
cd data-quality-dashboard
