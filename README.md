# Canadian Retail Customer Segmentation (RFM Analysis)

## 📌 Project Overview

This project focuses on analyzing Canadian retail customer purchasing behavior using SQL, Python, and Power BI.

The main objective is to clean retail transaction data, perform RFM (Recency, Frequency, Monetary) analysis, identify different customer segments, and build an interactive Power BI dashboard to generate meaningful business insights.

This end-to-end Data Analytics project demonstrates how raw retail data can be transformed into actionable business recommendations.

## 🎯 Business Objectives

- Clean and prepare raw retail transaction data using SQL.
- Analyze customer purchasing patterns using Python.
- Perform RFM analysis to understand customer value.
- Segment customers based on purchasing behavior.
- Build an interactive Power BI dashboard.
- Generate business insights to improve customer retention and revenue.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| SQL | Data cleaning and transformation |
| Python | Data analysis and RFM segmentation |
| Pandas | Data manipulation |
| NumPy | Numerical calculations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Power BI | Interactive dashboard |
| DAX | KPI calculations and measures |

## 📂 Project Workflow

### 1. SQL – Data Cleaning

Used SQL to clean and prepare the raw Canadian retail dataset.

Key activities:

- Checked and handled missing values.
- Identified and removed duplicate records where appropriate.
- Checked incorrect data types.
- Handled invalid transaction records.
- Validated customer and transaction information.
- Prepared clean data for further analysis.

### 2. Python – RFM Analysis

Used Python to perform customer segmentation using RFM methodology.

**RFM stands for:**

| Metric | Meaning | Business Purpose |
|---|---|---|
| Recency | How recently a customer purchased | Measures customer engagement |
| Frequency | How often a customer purchased | Measures customer loyalty |
| Monetary | How much a customer spent | Measures customer value |

Key activities:

- Imported cleaned data using Pandas.
- Performed exploratory data analysis (EDA).
- Calculated Recency, Frequency, and Monetary values.
- Assigned RFM scores.
- Created customer segments.
- Analyzed customer purchasing behavior.
- Exported RFM results for Power BI.

### 3. Power BI – Interactive Dashboard

Created an interactive Power BI dashboard to visualize customer segmentation and business performance.

Dashboard analysis includes:

- Total Customers
- Total Revenue
- Total Orders
- Average Customer Monetary Value
- Customer Segmentation
- Revenue by Customer Segment
- Customer Distribution
- RFM Analysis

## 👥 Customer Segmentation

The RFM methodology helps identify different customer groups.

| Segment | Description |
|---|---|
| Champions | Best and most valuable customers |
| Loyal Customers | Customers who purchase frequently |
| Potential Loyalists | Recent customers with growth potential |
| New Customers | Customers who recently purchased |
| At Risk | Customers who may stop purchasing |
| Hibernating | Inactive customers |

*Final segment names and definitions depend on the scoring logic implemented in Python.*



## 💡 Business Insights & Recommendations

- Identify high-value customers and provide loyalty rewards.
- Improve customer retention through targeted campaigns.
- Re-engage inactive customers with personalized offers.
- Increase repeat purchases through customer loyalty programs.
- Identify customer segments contributing the most revenue.
- Use customer behavior to improve marketing strategies.

## 📁 Project Structure

```text
Canadian-Retail-Customer-Segmentation-RFM/
│
├── Data/
│   └── Sample_Dataset.csv
│
├── SQL/
│   └── Data_Cleaning.sql
│
├── Python/
│   └── RFM_Analysis.ipynb
│
├── PowerBI/
│   └── RFM_Dashboard.pbix
│
├── Visualizations/
│   └── dashboard.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

*Adjust folder and file names to match your actual repository. Large datasets should be stored externally or shared through an appropriate data link.*

## ⚙️ How to Run the Project

**Step 1: Clone the repository**

```bash
git clone https://github.com/Dnyanu2027/Canadian-Retail-Customer-Segmentation-RFM.git
```

**Step 2: Install Python libraries**

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

**Step 3: Run Python analysis**

```bash
jupyter notebook
```

Open the RFM analysis notebook and execute the cells.

**Step 4: Open Power BI Dashboard**

Open the `.pbix` file using Microsoft Power BI Desktop.

## 📚 Skills Demonstrated

- SQL Data Cleaning
- Data Transformation
- Exploratory Data Analysis (EDA)
- Python Programming
- Pandas and NumPy
- RFM Customer Segmentation
- Data Visualization
- Power BI Dashboard Development
- Business Intelligence
- Business Insights and Recommendations

## 👩‍💻 Author

**Dnyaneshwari Madake**
Data Analyst

GitHub: [Dnyanu2027](https://github.com/Dnyanu2027)

---

⭐ If you find this project useful, please consider giving it a star!
