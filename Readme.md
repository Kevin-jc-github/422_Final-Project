# **422 Final Prject Used Car Price Prediction**

## **Team Members**
Introducing the talented individuals who contributed to this project:

1. Yate Zhang


2. Yuchen Bi


3. Chris Wang


4. Jiancong Zhu

## **Project Overview**
This project aims to develop a **machine learning model** to predict the prices of used cars listed on Craigslist. The dataset is sourced from Kaggle and contains a variety of vehicle attributes, including **brand, model, manufacturing year, mileage, fuel type, transmission, and more**. By applying **exploratory data analysis (EDA), data preprocessing, feature engineering, and machine learning models**, this project provides an end-to-end pipeline for price prediction.

The project follows the **CRISP-DM framework** to ensure a structured approach to data processing, model training, and evaluation. The final goal is to produce an **optimized predictive model** that can assist buyers and sellers in **accurately estimating** used car values.

---

## **Dataset**
- **Source:** [Kaggle - Craigslist Cars & Trucks Dataset](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data)
- **Number of Records:** 426,880
- **Number of Features:** 26
- **Data Type:** Mixed (Numerical & Categorical)

### **Key Columns**
- `price`: The price of the used car (Target variable)
- `year`: The manufacturing year of the car
- `manufacturer`: The brand of the vehicle (e.g., Toyota, Ford, BMW)
- `model`: The specific model of the car
- `odometer`: The total miles driven
- `fuel`: The type of fuel used (e.g., Gasoline, Diesel, Electric)
- `transmission`: The transmission type (e.g., Automatic, Manual)
- `drive`: The drivetrain (e.g., FWD, RWD, 4WD)
- `paint_color`: The color of the car

---

## **Project Structure**
```plaintext
📂 Craigslist-Car-Price-Prediction
│── 📂 data                    # Dataset directory (Optional: Raw & Processed data)
│── 📂 notebooks                # Jupyter notebooks for EDA, preprocessing & modeling
│── 📂 models                   # Trained machine learning models
│── 📂 scripts                  # Python scripts for preprocessing, feature engineering, and training
│── ├── preprocess.py          # Data preprocessing & feature engineering script
│── ├── train_model.py         # Machine learning model training script
│── ├── evaluate_model.py      # Model evaluation & visualization script
│── ├── requirements.txt       # Required Python packages
│── README.md                   # Project documentation
