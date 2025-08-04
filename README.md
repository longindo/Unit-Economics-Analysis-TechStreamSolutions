# 📊 Unit Economics Analysis - Streamline Pro

## 🎯 Project Overview

This project conducts a **business performance analysis** for **Streamline Pro** - a Software as a Service (SaaS) platform by TechStream Solutions.

**Business performance analysis** focuses on calculating costs and profits from each customer, including:
- 💰 Cost to acquire a new customer (Customer Acquisition Cost - CAC)
- 📊 Average revenue from each customer (Average Revenue Per User - ARPU) 
- 🔄 Total value a customer brings throughout their service usage period (Customer Lifetime Value - LTV)

**Objective:** Evaluate profitability and effectiveness of marketing, sales, and retention strategies based on March 2023 data.

**Technology Stack:**
- **Python** in Google Colab environment
- **Pandas** for data processing and analysis
- **Matplotlib/Seaborn** for data visualization

## 📂 Data Sources

Data is sourced from Google Drive and includes the following files:

| File | Description |
|------|-------------|
| `daily_marketing_spending.xlsx` | Daily marketing spend by channel |
| `customer_lifespan_data.xlsx` | Customer lifecycle data (start date, churn date) |
| `receipts_history.xlsx` | Revenue history from transactions |
| `Monthly expenses.xlsx` | Monthly operational expenses |
| `Payroll.xlsx` | Employee salary costs by month and department |

## 📈 Unit Economics Metrics

### Analysis Results for March 2023:

| Metric | English Name | Value |
|--------|--------------|-------|
| Customer Acquisition Cost | CAC | $50 |
| Average Revenue Per User | ARPU | $75 |
| Cost of Goods Sold | COGS | $25 |
| Gross Margin | Gross Margin | $50 |
| Gross Margin Percentage | Gross Margin % | 66.67% |
| Customer Lifetime Value | LTV | $2,000 |
| **LTV/CAC Ratio** | **LTV/CAC Ratio** | **40** |

> ⚠️ **Note:** The values above are illustrative examples. Please refer to the `Unit_Economics_with_Python.ipynb` file for detailed calculations and actual results.

## 🚀 How to Use

1. **Prepare Data:**
   - Ensure Excel files are uploaded to Google Drive
   - Verify data access paths

2. **Open Google Colab:**
   - Access [Google Colab](https://colab.research.google.com)
   - Upload the `Unit_Economics_with_Python.ipynb` file
   - Connect to Google Drive containing the data

3. **Run Analysis:**
   - Execute each cell in the notebook sequentially
   - View detailed visualizations and reports

## 🎯 Results and Insights

### ✅ Key Findings

Streamline Pro demonstrates a **strong and sustainable business model**:

- **LTV/CAC Ratio = 40** (far exceeds the ideal threshold of 3)
- **Low customer acquisition cost** with high marketing efficiency
- **Low churn rate** indicating good product quality
- **66.67% gross margin** showing high profitability

### 💡 Strategic Recommendations

1. **Optimize Marketing:**
   - Analyze marketing channels in detail to identify lowest CAC
   - Allocate budget to most effective channels

2. **Scale Operations:**
   - Leverage strong financial foundation to expand operations
   - Increase marketing budget to capture market share

3. **Enhance Retention:**
   - Invest in product improvements and customer support
   - Maintain low churn rate to maximize LTV

## 🔗 Important Links

- 📓 [Jupyter Notebook](link-to-notebook)
- 📁 [Data Folder](link-to-data-folder)
- 📊 [Visualization Dashboard](link-to-dashboard) *(if available)*

## 👨‍💻 Author Information

**Author:** Max
**Email:** baolong.indo@gmail.com 
**Completion Date:** 03.08.

## 📋 System Requirements

- Python 3.7+
- Google Colab or Jupyter Notebook
- Google Drive access

### Required Libraries:
```python
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
numpy>=1.21.0
openpyxl>=3.0.0  # For reading Excel files
```

*This project is part of business analysis for TechStream Solutions. For questions and feedback, please contact via email or create an issue in the repository.*
