# Domain-Oriented-Case-Study-BFSI
# :bank: **Loan Default Risk Analysis - EDA Case Study** :chart_with_upwards_trend:

## :rocket: **Introduction**
This case study aims to demonstrate the application of **Exploratory Data Analysis (EDA)** in a real-world business problem within the banking and financial services sector. The goal is to analyze customer loan data and identify patterns that indicate a higher likelihood of loan default. By doing so, the company can make better decisions to reduce financial risk while ensuring that applicants capable of repaying the loan are not rejected.

## :clipboard: **Business Understanding**

Loan-providing companies face significant risks when approving loans, especially when applicants have limited or no credit history. Some consumers take advantage of this situation by defaulting on loans. This case study is centered around a **consumer finance company** that provides loans to urban customers. The company aims to use EDA to identify patterns in loan applications that indicate whether an applicant is likely to default.

### **Types of Risks:**
1. **Loss of Business Risk**: Not approving loans for clients who are likely to repay them.
2. **Financial Loss Risk**: Approving loans for clients who are likely to default.

### **Decision Types:**
- **Approved**: The loan application is approved by the company.
- **Cancelled**: The client cancels the application.
- **Refused**: The loan is rejected due to insufficient qualifications.
- **Unused Offer**: The client cancels the loan at a different stage of the process.

---

## :bar_chart: **Business Objectives**

The objectives of this case study are:
1. **Identify Default Indicators**: Use EDA to identify the key drivers of loan defaults, such as income, loan type, and payment history.
2. **Improve Decision-Making**: Utilize these insights to:
   - Deny loans to high-risk applicants.
   - Offer loans at higher interest rates to risky clients.
   - Reduce loan amounts for clients who are likely to default.
3. **Risk Assessment**: Use identified patterns to assess the overall lending risk.

---

## :file_folder: **Data Understanding**

This case study utilizes three datasets:

### 1. `application_data.csv`
Contains detailed information about the client's application, including demographic information and loan attributes such as income, loan amount, loan purpose, etc.

### 2. `previous_application.csv`
Contains information about the client's previous loan history, including the approval status (Approved, Cancelled, Refused, Unused Offer) of past loan applications.

### 3. `columns_description.csv`
A data dictionary that explains the meaning and significance of each variable in the datasets.

---

## :hammer_and_wrench: **Approach**

### **1. Data Preprocessing**
- **Loading Data**: Load and explore the datasets to understand their structure.
- **Data Cleaning**: Handle missing data, duplicates, and outliers.
- **Feature Engineering**: Combine data from `application_data.csv` and `previous_application.csv` to create new features, such as the number of previous loans or loan approval history.

### **2. Exploratory Data Analysis (EDA)**
- **Univariate Analysis**: Analyze the distribution of each variable (e.g., income, loan amount, payment history).
- **Bivariate Analysis**: Examine the relationships between potential default indicators (e.g., income and loan approval status).
- **Correlation Analysis**: Identify relationships between numerical features to detect multicollinearity or strong associations.

### **3. Risk Indicators**
- Identify the strongest risk indicators based on the EDA results, such as:
  - Client income and loan amount.
  - Previous loan history and default status.
  - Demographic information (age, employment status).
  - Loan type and purpose.

### **4. Visualizations**
- **Correlation Heatmap**: Visualize the relationships between numerical features.
- **Distribution Plots**: Histograms and box plots to show the distribution of key variables.
- **Categorical Plots**: Bar or count plots to visualize the distribution of categorical variables (loan approval status, loan type).

### **5. Conclusions and Insights**
- Summarize the key findings from the analysis, such as the primary drivers of loan defaults.
- Provide recommendations based on these findings, such as:
  - Denying loans to high-risk applicants.
  - Reducing loan amounts or offering higher interest rates to risky clients.

---

## :wrench: **Tools and Libraries Used**
- **Pandas**: For data manipulation and analysis.
- **Matplotlib** / **Seaborn**: For data visualization.
- **NumPy**: For numerical computations.
- **Scikit-learn** (optional): For predictive modeling.

---

## :trophy: **Conclusion**
By applying **Exploratory Data Analysis (EDA)** to the loan application data, the company can gain valuable insights into the factors that contribute to loan defaults. These insights will help improve decision-making processes, reduce risk, and ensure that applicants who can repay loans are not rejected.

---

**Feel free to modify this README based on your specific findings or approach.** Let me know if you need further changes or additional sections to enhance the document!



