# Bank Loan Default Risk Analysis (Credit EDA)
*A Case Study in Risk Analytics for Banking & Financial Services*

## 🔍 Project Overview
This project applies Exploratory Data Analysis (EDA) to a real-world banking scenario. The objective is to identify patterns in loan application data to minimize financial loss. By understanding the "drivers" of default, the bank can ensure that credit-worthy applicants are approved while high-risk individuals are identified.

## 📁 Repository Structure
- **[data/](./data/):** Contains the raw loan application dataset.
- **[docs/](./docs/):** Contains the [Business Presentation PDF](./docs/credit%20EDA%20assignment.pdf) with executive summaries and visual insights.
- **[notebooks/](./notebooks/):** Contains the [Technical Jupyter Notebook](./notebooks/Credit%20EDA%20assignment-checkpoint.ipynb) with Python implementation.

## 📈 Key Insights & Conclusions
Based on the analysis of ~300k records, the following risk patterns were identified:
- **Demographics:** Default rates for female customers are significantly lower than males. Married individuals and those with higher education are the safest segments to target.
- **Occupation & Employment:** Drivers and low-skill laborers show the highest default rates, while Accountants and Pensioners are among the safest.
- **Asset Ownership:** Clients who own their house or apartment show a higher repayment consistency.
- **Loan Type:** Most defaults occur in **'Cash Loans'** rather than 'Revolving Loans'. 
- **Income Bracket:** Most defaulters fall within the income range of 0 to 1 million, especially when the credit amount is less than 1.5 million.

## 🛠️ Tools & Technologies Used
- **Python** (Pandas, NumPy)
- **Visualization:** Seaborn, Matplotlib
- **Analysis:** Univariate, Bivariate, and Multivariate Analysis, Outlier Treatment, Handling Data Imbalance.

## 🎓 Academic Context
This project was completed as part of the **Executive PG Programme in Data Science and AI at IIIT Bangalore** (in association with upGrad).
