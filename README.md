# 📊 Data Visualization Dashboard

A comprehensive data visualization project analyzing sales performance across products, territories, and time periods using Python data science libraries.

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Pandas](https://img.shields.io/badge/Pandas-Latest-150458.svg)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Latest-11557c.svg)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Latest-3776AB.svg)](https://seaborn.pydata.org/)

## 🎯 Project Overview

This project demonstrates professional-level data analysis and visualization capabilities through a detailed examination of sales data. The dashboard provides actionable insights into sales trends, product performance, regional distribution, and customer behavior using industry-standard Python libraries.

**Dataset Source:** [Kaggle - Sample Sales Dataset](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)

## 🌟 Key Features

- **Time Series Analysis** - Monthly sales trends and seasonality detection
- **Product Performance** - Comparative analysis across product lines
- **Regional Intelligence** - Territory-based sales heatmaps
- **Advanced Visualizations** - Multiple chart types using Seaborn
- **Statistical Insights** - Correlation analysis and distribution patterns
- **Clean Code Architecture** - Well-documented, modular Python code

## 📁 Project Structure

```
Data_visualization_dashboard/
│
├── data/
│   └── sales_data_sample.csv          # Raw sales dataset
│
├── notebooks/
│   └── analysis.ipynb          # Jupyter notebook 
├── .gitignore                   # Git ignore rules
├── README.md                   # Project 
```

## 🔍 Analysis Components

### 1. Monthly Sales Trend Analysis
**Visualization:** Line Chart  
**Purpose:** Identifies seasonal patterns, peak sales periods, and overall growth trajectory

**Key Insight:** October 2003 showed the highest sales volume, suggesting strong seasonal demand during Q4.

### 2. Product Line Performance
**Visualization:** Bar Chart  
**Purpose:** Compares total revenue contribution across different product categories

**Key Insight:** Motorcycles emerged as the top-performing product line, accounting for the largest share of total sales.

### 3. Regional Sales Distribution
**Visualization:** Heatmap  
**Purpose:** Cross-analyzes sales performance by territory and product line

**Key Insight:** EMEA territory demonstrated strong performance in Motorcycles, while North America led in Classic Cars sales.

### 4. Advanced Statistical Visualizations

- **Countplot** - Order frequency distribution across product lines
- **Boxplot** - Sales variability and outlier detection
- **Violin Plot** - Sales density distribution by territory and product
- **Swarmplot** - Granular view of individual sales transactions
- **Pairplot** - Multivariate relationship analysis
- **Correlation Heatmap** - Numerical feature correlation matrix

### 5. Business Intelligence Insights

- **Top Performing Product:** Motorcycles
- **Highest Revenue Territory:** EMEA
- **Peak Sales Period:** October 2003
- **Sales Distribution:** Statistical analysis of order values
- **Customer Segmentation:** Top customers by revenue contribution

## 🛠️ Technologies Used

- **Python 3.8+** - Core programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Static visualizations
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.8 or higher
pip package manager
```

### Installation

1. Clone the repository
```bash
git clone git clone https://github.com/Basantkhanal07/Data_visualization_dashboard
```

2. Create a virtual environment (recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages
```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook
```bash
jupyter notebook notebooks/analysis.ipynb
```

## 📊 Dataset Information

The dataset contains comprehensive sales records with the following attributes:

| Column | Description |
|--------|-------------|
| `ORDERNUMBER` | Unique order identifier |
| `ORDERDATE` | Date of transaction |
| `PRODUCTLINE` | Product category |
| `PRODUCTCODE` | Unique product identifier |
| `QUANTITYORDERED` | Number of units ordered |
| `PRICEEACH` | Unit price |
| `SALES` | Total sales amount |
| `TERRITORY` | Geographic sales region |
| `COUNTRY` | Customer country |
| `CUSTOMERNAME` | Customer identifier |

**Total Records:** 2,823 transactions  
**Date Range:** 2003-2005  
**Product Lines:** 7 categories

## 📈 Sample Visualizations

### Monthly Sales Trend
Tracks revenue patterns over time, revealing seasonal fluctuations and growth trends.

### Product Line Comparison
Highlights which product categories drive the most revenue.

### Regional Heatmap
Identifies geographic strengths and opportunities for market expansion.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 🙏 Acknowledgments

- Dataset provided by Kaggle community
- Inspired by real-world business intelligence requirements
- Built with guidance from data visualization best practices

---

⭐ If you find this project useful, please consider giving it a star on GitHub!

**Last Updated:** January 2026