# Predicting Last-Mile Delivery Delays in E-Commerce Using Machine Learning

---

## Project Overview

This project focuses on predicting last-mile delivery delays in e-commerce logistics using machine learning techniques. The analysis is based on the Olist Brazilian E-Commerce Public Dataset, which contains over 115,000 customer orders recorded between 2016 and 2018.

The objective is to identify the factors that influence delivery performance and build predictive models that can help logistics companies improve operational efficiency, customer satisfaction, and supply chain decision-making.

---

## Project Objectives

* Analyze delivery performance patterns in e-commerce logistics.
* Perform data cleaning, preprocessing, and feature engineering.
* Develop and compare multiple machine learning models.
* Evaluate model performance using standard regression metrics.
* Create an interactive Power BI dashboard to visualize key business insights.

---

## Dataset

**Dataset:** Olist Brazilian E-Commerce Public Dataset

The dataset includes information related to:

* Orders
* Customers
* Sellers
* Products
* Payments
* Reviews
* Delivery timelines

**Source:** https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* Google Colab
* Power BI

---

## Machine Learning Models Evaluated

| Model                   | MAE  | RMSE  | R² Score |
| ----------------------- | ---- | ----- | -------- |
| Linear Regression       | 6.76 | 10.21 | 0.005    |
| Decision Tree Regressor | 7.24 | 12.19 | -0.420   |
| Random Forest Regressor | 5.44 | 8.83  | 0.255    |
| XGBoost Regressor       | 6.07 | 9.30  | 0.175    |

---

## Best Performing Model

### Random Forest Regressor

**Performance Metrics**

* Mean Absolute Error (MAE): **5.44 days**
* Root Mean Squared Error (RMSE): **8.83 days**
* R² Score: **0.255**

The Random Forest model achieved the best overall performance among all evaluated models, demonstrating the effectiveness of ensemble learning techniques for delivery delay prediction.

---

## Repository Structure

```text
olist-delivery-delay-prediction/
│
├── data/
│
├── notebooks/
│   ├── data_preprocessing.ipynb
│   └── model_training.ipynb
│
├── powerbi/
│   └── delivery_dashboard.pbix
│
├── reports/
│   └── project_report.pdf
│
└── README.md
```

---

## Key Outcomes

* Built predictive models to estimate delivery delays.
* Identified important factors affecting order fulfillment performance.
* Compared multiple machine learning algorithms using regression metrics.
* Demonstrated the effectiveness of Random Forest for logistics prediction.
* Developed an interactive Power BI dashboard for business-oriented analysis and decision-making.

---

## Future Improvements

* Incorporate external factors such as weather conditions and traffic data.
* Explore advanced ensemble and deep learning models.
* Deploy the model as a web application for real-time predictions.
* Improve feature engineering to increase prediction accuracy.

---

## Dashboard

The Power BI dashboard provides insights into:

* Delivery performance trends
* Delay distribution analysis
* Seller and customer performance metrics
* Regional delivery patterns
* Key business KPIs

---

## License

This project is intended for educational, research, and portfolio purposes.

---


