# Mumbai-House-Price-Analysis
Data Analysis and Machine Learning project using Python and Power BI.
#  Mumbai House Price Analysis

##  Project Overview

The **Mumbai House Price Analysis** project analyzes residential property prices across different localities in Mumbai using **Python, Machine Learning, and Power BI**. The objective is to identify property price trends, compare localities, discover key factors affecting house prices, and build predictive models for house price estimation.

This project demonstrates an end-to-end data analytics workflow, including data cleaning, exploratory data analysis (EDA), data visualization, machine learning, and dashboard creation.

---

##  Objectives

* Clean and preprocess housing data.
* Perform Exploratory Data Analysis (EDA).
* Analyze price trends across Mumbai localities.
* Calculate average price per square foot.
* Identify the most expensive and affordable areas.
* Compare property prices by BHK, region, property type, and property age.
* Build machine learning models to predict house prices.
* Develop an interactive Power BI dashboard.

---

##  Dataset Features

| Feature        | Description                        |
| -------------- | ---------------------------------- |
| bhk            | Number of Bedrooms                 |
| type           | Property Type                      |
| locality       | Property Locality                  |
| area           | Carpet Area (Sq.ft)                |
| price          | Property Price                     |
| price_unit     | Price Unit                         |
| region         | Region of Mumbai                   |
| status         | Ready to Move / Under Construction |
| age            | Property Age                       |
| price_per_sqft | Price per Square Foot              |

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Power BI
* Git & GitHub

---

##  Exploratory Data Analysis

The following analyses were performed:

* Average House Price
* Highest & Lowest Property Price
* Area-wise Price Analysis
* Top 10 Expensive Localities
* Top 10 Affordable Localities
* BHK Distribution
* Average Price per Square Foot
* Region-wise Analysis
* Property Type Analysis
* Property Age Analysis
* Property Status Analysis

---

##  Visualizations

The project includes:

* Histogram of House Prices
* Area-wise Price Bar Chart
* BHK Distribution Donut Chart
* Average Price by Region
* Top 10 Expensive Localities
* Average Price per Sq.ft
* Property Type Chart
* Property Status Chart
* Property Age Analysis
* Correlation Heatmap
* Scatter Plot (Area vs Price)

---

##  Machine Learning Models

The following regression algorithms were implemented:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

### Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

The best-performing model was selected based on the highest R² score and lowest prediction error.

---

##  Power BI Dashboard

The dashboard contains:

### KPI Cards

* Total Houses
* Average Price
* Highest Price
* Lowest Price

### Charts

* Area-wise Price
* BHK Distribution
* Average Price by Region
* Top 10 Expensive Localities
* Property Status
* Property Type
* Property Age Analysis
* Region-wise House Count

### Interactive Filters

* Locality
* Region
* BHK
* Price Range

---

##  Project Structure

```
Mumbai-House-Price-Analysis/
│
├── data/
│   └── mumbai_house_prices_cleaned.csv
│
├── notebooks/
│   └── House_Price_Analysis.ipynb
│
├── powerbi/
│   └── Mumbai_House_Price_Dashboard.pbix
│
├── images/
│   ├── dashboard.png
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 💡 Key Insights

* Identified premium and affordable localities in Mumbai.
* Compared house prices across different regions.
* Analyzed the relationship between carpet area and price.
* Studied the impact of BHK, property type, and property age on pricing.
* Built predictive models for estimating house prices.
* Designed an interactive Power BI dashboard for business decision-making.

---

##  Future Improvements

* Add latitude and longitude for interactive map visualization.
* Deploy the machine learning model as a web application using Streamlit or Flask.
* Integrate live property data from real estate APIs.
* Perform advanced feature engineering and hyperparameter tuning.

---

##  Author

**Saloni**

MCA Student | Data Analytics Enthusiast

---

## ⭐ If you found this project useful, please consider giving it a Star on GitHub!
