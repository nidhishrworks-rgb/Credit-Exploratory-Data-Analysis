### 🔍 Project Overview
**Credit EDA:** Analyzing loan application data to identify patterns of **default risk**. 

* **Goal:** Explore demographics, income, and credit history.
  
* **Tools:** Python (Pandas, Seaborn).
  
* **Impact:** Uncover variables influencing repayment to minimize financial loss and optimize loan approval strategies.


🛠️ Data Processing & Cleaning
Before analysis, the dataset underwent several preprocessing steps to ensure accuracy:

Missing Value Analysis: Identified columns with high null percentages and applied appropriate imputation or removal.

Outlier Detection: Used box plots to identify and handle anomalies in Income and Credit Amount.

Data Transformation: Standardized categorical variables and converted "Days of Birth" into readable "Age" columns.

Feature Engineering: Created new ratios, such as Income-to-Annuity and Credit-to-Goods-Price, to better understand client leverage


📈 Analysis Focus Areas
We explored the data through three main lenses:

Univariate Analysis: Examining the distribution of the target variable and client demographics.

Bivariate Analysis: Comparing Target (Defaulters vs. Non-Defaulters) against variables like Education, Occupation, and Gender.

Correlation Analysis: Utilizing heatmaps to find strong relationships between external data scores and loan repayment

💡 Expected Insights
Risk Profiles: Identifying which age groups and employment sectors carry the highest default risk.

Credit Patterns: Determining if high-value loans are more prone to default than smaller, short-term credits.

Indicators: Evaluating if the presence of a co-applicant or specific housing types affects the repayment rate.

* ## 🚀 Getting Started
1. Clone the repository: `git clone https://github.com/yourusername/credit-eda.git`
 
2. Install dependencies: `pip install -r requirements.txt`
 
3. Open the notebook: `jupyter notebook notebooks/credit_eda.ipynb`
