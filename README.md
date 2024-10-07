# sales-analysis-trial
## sales analysis data of x company over 2 consecutive months
---

# Introduction 

## Table Of Contents

### Project Overview



This is a python and SQL project on an imaginary supermarket called Nasa Supermarket
the analysis project objectives is to analyze and glean insight into the sales performance 
of Nasa supermarket for the year 2023 .By analyzing various aspects of the sales data,we
want to identify trends,make data_driven recommendation,and gain a deeper understanding of 
the supermarket's(company) performance to answer critical questions and help the supermarket 
make data-driven decisions.Disclaimer:All dataset and reports here do not represent any company,
institution or state but just a dummy dataset to demonstrate the power of python and SQL in data
analysis

### Data Source

sales data:

the primary dataset used for this analysis is the 
"sales_data.csv" file , containing detail information about
each sale made by the supermarket for the period under review.

### Tools

 - Excel

 - Python 

 - Power BI Creating reportsData Loading and Inspection 
    2.Handling missing values 
    3.Data cleaning and formatting

### Data Cleaning/Preparation

 in the initial data preparation phase,i performed the following tasks:

 1 Data Loading and Inspection 
 
 2.Handling missing values 
 
 3.Data cleaning and formatting

### Exploratory Data Analysis
EDA provides the means to exploring the sales data to answer critical questions such as:
 
### Data Analysis

some interesting codes/features worked with

```Python
sales_df = pd.read_csv("C:/Users/Nasa/Databankanalysis/Dataframes/sales.csv")
```

```Python
sales.columns = [i.lower()for I in sales.columns]
```

```Sql
select * from sales
```
