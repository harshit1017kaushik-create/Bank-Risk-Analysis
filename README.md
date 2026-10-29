# Ledger Signal — Bank Customer & Credit Analytics

An end-to-end banking analytics project using **Python, Pandas, Jupyter Notebook, and Power BI** to explore retail banking customers, financial product balances, loyalty segments, income bands, and relationships across banking variables.

**Live Website:** https://harshit1017kaushik-create.github.io/Bank-Risk-Analysis/
---

## Project Overview

This project analyzes a dataset of 3,000 retail banking customer records to understand customer characteristics, financial product distribution, banking balances, and relationships between financial variables.

The analysis was performed in Python using Jupyter Notebook, followed by the development of an interactive Power BI report containing an executive overview and detailed analysis pages.

The project demonstrates a complete data analytics workflow, from loading and checking the data to exploratory analysis, correlation analysis, visualization, and business insight communication.

## Objectives

- Understand the distribution of customers across income bands, gender, age groups, and loyalty classifications.
- Analyze bank deposits, bank loans, business lending, savings accounts, and checking accounts.
- Explore relationships between numerical banking variables using correlation analysis.
- Compare financial activity across customer segments.
- Communicate key findings through an interactive Power BI report and a portfolio website.

## Technology Stack

| Technology             | Purpose                                        |
| ---------------------- | ---------------------------------------------- |
| Python                 | Data analysis and processing                   |
| Pandas                 | Data loading, inspection, and manipulation     |
| NumPy                  | Numerical operations                           |
| Matplotlib and Seaborn | Exploratory visualizations                     |
| Jupyter Notebook       | Analysis workflow and documentation            |
| Power BI               | Interactive dashboards and financial reporting |
| CSV                    | Dataset storage and exchange                   |
| HTML, CSS, JavaScript  | Project portfolio website                      |

## Dataset

**File:** `Banking.csv`

The dataset contains **3,000 rows and 25 columns**, representing retail banking customers and their financial information.

The analysis covers:

- Customer demographics, including age, gender, and nationality
- Occupation and estimated income
- Income bands: Low, Med, and High
- Loyalty classifications: Jade, Silver, Gold, and Platinum
- Bank deposits and loans
- Business lending
- Savings and checking account balances
- Credit card balances and number of credit cards
- Property ownership

The project uses the provided dataset for portfolio and educational analysis. Please verify that the data is safe to publish before sharing it publicly.

## Analysis Workflow

### 1. Data Loading and Quality Checks

- Loaded the banking dataset into Pandas.
- Inspected the dataset's dimensions and data types.
- Checked for missing values and duplicate client records.
- Created income bands to support segment-level comparisons.

The existing project records zero missing values and zero duplicate client records.

### 2. Exploratory Data Analysis

Performed univariate and bivariate analysis to investigate customer distributions and financial activity.

Key areas included:

- Customer distribution by gender, nationality, age group, and loyalty classification
- Income-band distribution
- Bank deposits and loans by income band
- Financial product balances by loyalty tier
- Distribution of credit card ownership

### 3. Correlation Analysis

Calculated correlations between numerical banking variables and examined selected relationships using scatter plots and regression visualizations.

Selected findings from the existing analysis:

| Variable relationship               | Pearson correlation |
| ----------------------------------- | ------------------: |
| Bank Deposits and Checking Accounts |                0.84 |
| Bank Deposits and Saving Accounts   |                0.75 |
| Business Lending and Bank Loans     |                0.42 |

These results indicate positive linear associations in the analyzed dataset. Correlation does not establish causation.

### 4. Power BI Dashboard

Created a multi-page banking analytics report featuring:

- Executive financial overview
- Loan and lending analysis
- Deposit analysis
- Customer analysis
- Income-band and loyalty-classification comparisons
- Customer demographics and credit card distribution

The report includes KPI cards, charts, slicers, and segment-level comparisons.

## Key Findings

The following values are displayed in the existing Power BI report and portfolio website.

| Metric                    | Reported value |
| ------------------------- | -------------: |
| Total customers           |          3,000 |
| Total estimated income    |        513.92M |
| Total bank deposits       |         2.01bn |
| Total bank loans          |         1.77bn |
| Total business lending    |         2.60bn |
| Total checking accounts   |        963.28M |
| Total savings accounts    |        698.73M |
| Total credit card balance |          9.53M |

Additional observations from the analysis:

- The Med income band contains 1,517 customers (50.6%), followed by Low with 1,027 (34.2%) and High with 456 (15.2%).
- Jade is the largest loyalty segment by customer count, with 1,331 customers (44.37%).
- Bank deposits and checking accounts have the strongest reported linear relationship among the selected pairs.
- Adult and senior-citizen customers have higher average bank deposits than young customers in the analyzed report.
- Properties Owned has weak linear relationships with the other banking variables examined.

Financial amounts are reproduced as displayed in the report; they have not been independently recalculated for this README.

## Repository Structure

```text
Bank-Risk-Analysis/
├── README.md
├── Banking.csv
├── Bank_Analysis.ipynb
└── Bank_Analysis.pbix        
                  
```


## How to Run the Project

1. Clone or download this repository.

2. Install Python and Jupyter Notebook.

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Open `Project_2.ipynb` in Jupyter Notebook.

5. Place `Banking.csv` at the path expected by the notebook, or update the file path.

6. Run the notebook cells in order to reproduce the analysis.

7. Open `Project2_reports.pdf` to review the dashboard report, or use Power BI Desktop to open the `.pbix` file if it is included.

## Project Deliverables

- Jupyter Notebook containing data analysis and visualizations
- Banking dataset in CSV format
- Power BI report in PDF format
- Optional Power BI Desktop report (`.pbix`)
- Portfolio website presenting the workflow and findings

## Limitations

- The analysis describes patterns in the provided dataset and does not establish causal relationships.
- The project focuses on customer and financial portfolio analytics.
- No loan-default target or validated default-prediction model is documented in the provided project materials.
- The reported financial metrics should be interpreted in the context of the supplied dataset.

## Author

**Harshit Kaushik**

B.Tech — Computer Science & Engineering

Interested in Data Analytics, Business Intelligence, Python, SQL, and Power BI.

**Portfolio:** [Add your website URL]
**GitHub:** [https://github.com/harshit1017kaushik-create](https://github.com/harshit1017kaushik-create)
