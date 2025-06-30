# Sales Forecasting Using Linear Regression – Superstore Dataset

## Project Overview

This project presents a linear regression-based approach to forecasting future monthly sales using a retail Superstore dataset. It covers the entire data analytics pipeline—from preprocessing and feature engineering to model development and visualization. The primary goal is to provide actionable sales predictions that support strategic planning and business decision-making.

---

## Objective

To forecast the next six months of sales by leveraging historical transaction data. The model is designed to help businesses anticipate demand, allocate resources effectively, and optimize revenue generation strategies.

---

## Dataset

- **Source**: Retail Superstore dataset (CSV format)
- **Key Variables**:
  - `Order Date`: Date of each transaction
  - `Sales`: Revenue generated
- **Derived Features**:
  - `YearMonth`: Extracted from order dates for time-series aggregation
  - `MonthNumber`: Sequential numeric representation of months for regression input

---

## Methodology

### 1. Data Preprocessing
- Loaded and parsed the dataset using `pandas`
- Converted `Order Date` to datetime format
- Checked for data consistency and formatting issues

### 2. Feature Engineering
- Created `YearMonth` for monthly aggregation
- Aggregated total monthly sales for trend analysis
- Introduced `MonthNumber` as a numeric independent variable

### 3. Model Building
- Used **Linear Regression** from `scikit-learn` to model the relationship between month number and sales
- Trained the model on historical monthly sales data

### 4. Forecasting
- Predicted sales for the next six months using the fitted model
- Printed and visualized future forecasted values

### 5. Data Visualization
- Line plot comparing actual vs. forecasted monthly sales
- Bar chart for yearly sales comparison
- Scatter plot with regression trend line for monthly sales

---

## Key Results

**Forecasted Sales Output**  
Example of the model's predicted sales:
![image](https://github.com/user-attachments/assets/ffdabbc8-8927-48a5-bb68-720c8af11a7f)
- 2019-01: $68,879.00
- 2019-02: $69,767.31
- 2019-03: $70,655.62
- 2019-04: $71,543.93
- 2019-05: $72,432.25
- 2019-06: $73,320.56

---


---

## Skills Demonstrated

- Data preprocessing and time series aggregation using `pandas`
- Feature engineering for regression modeling
- Linear Regression with `scikit-learn`
- Data visualization with `matplotlib`
- Interpreting model outputs for business forecasting
- Communicating results clearly through professional plots and structured reporting

---

## Tools and Technologies

- **Programming Language**: Python
- **Libraries**: pandas, numpy, matplotlib, scikit-learn
- **Development Environment**: Google Colab

---

## Business Applications

- Forecasting sales to guide marketing and inventory strategies
- Identifying growth patterns and seasonal trends
- Supporting data-driven decisions in retail management

---

## Opportunities for Improvement

- Introduce advanced models such as **ARIMA** or **Facebook Prophet** for improved accuracy
- Integrate performance metrics (e.g., MAE, RMSE) for model evaluation
- Segment forecasts by region, category, or customer segment
- Deploy an interactive dashboard using Streamlit or Power BI

---

## About the Author

**Ajay Sudhakar Gande**  
M.Sc. Data Science | Aspiring Data Scientist / Data Analyst / BI Analyst  
📧 Email: ajaygande1@gmail.com  
🔗 LinkedIn: [linkedin.com/in/ajay-gande-5a38b2273](https://www.linkedin.com/in/ajay-gande-5a38b2273)

---

## Conclusion

This project showcases the practical application of foundational machine learning techniques to real-world business challenges. It reflects strong capabilities in data analysis, model development, and clear communication of results—essential skills for data-driven decision-making roles.
