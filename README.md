# Predicting Last-Mile Delivery Delays in E-Commerce Using Machine Learning

**Master’s Thesis Project**  
**Author:** Chiramani Saiteja  
**Year:** 2026

## Project Overview

This project investigates the prediction of last-mile delivery delays in e-commerce logistics using machine learning techniques. It uses the Olist Brazilian E-Commerce Public Dataset, which contains more than 115,000 customer orders recorded between 2016 and 2018.

The main goal of this study is to identify the key factors that influence delivery performance and build predictive models that can help logistics providers improve operational efficiency, customer satisfaction, and supply chain decision-making.

## Research Objectives

- Analyze delivery performance patterns in e-commerce logistics.
- Perform data cleaning, preprocessing, and feature engineering.
- Develop and compare multiple machine learning models.
- Evaluate model performance using standard regression metrics.
- Visualize key insights through an interactive Power BI dashboard.

## Dataset

**Dataset Used:** Olist Brazilian E-Commerce Public Dataset

The dataset includes information on:

- Orders
- Customers
- Sellers
- Products
- Payments
- Reviews
- Delivery timelines

**Source:** [Kaggle Dataset Page](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce?utm_source=chatgpt.com)

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Google Colab
- Power BI

## Machine Learning Models Evaluated

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 6.76 | 10.21 | 0.005 |
| Decision Tree Regressor | 7.24 | 12.19 | -0.420 |
| Random Forest Regressor | 5.44 | 8.83 | 0.255 |
| XGBoost Regressor | 6.07 | 9.30 | 0.175 |

## Best Performing Model

The **Random Forest Regressor** achieved the best performance among the evaluated models.

**Performance Summary:**

- MAE: 5.44 days
- RMSE: 8.83 days
- R² Score: 0.255

## Repository Structure

```bash
olist-delivery-delay-prediction/
├── data/
├── notebooks/
│   ├── data_preprocessing.ipynb
│   └── model_training.ipynb
├── powerbi/
│   └── thesis_dashboard.pbix
├── thesis/
│   └── THESIS_CHIRAMANI_SAITEJA_2026.pdf
└── README.md
```

## Key Outcomes

- Developed predictive models for delivery delay estimation.
- Identified delivery-related factors affecting order fulfillment performance.
- Demonstrated the effectiveness of ensemble learning methods for logistics prediction tasks.
- Created an interactive Power BI dashboard for business-oriented insights.

## Author

**Chiramani Saiteja**  
MSc Data Science and Business Analysis  
2026
