# 🚦 Smart City Traffic Volume Forecasting

This project is part of a 4-week internship where I developed a machine learning pipeline to predict hourly traffic volumes at different city junctions. The goal was to assist smart infrastructure planning using real-time and historical traffic data.

## 📌 Problem Statement
Forecast hourly vehicle flow at junctions using historical traffic data to help city authorities plan and manage traffic effectively.

## 📂 Dataset
- Train: `train_aWnotuB.csv` (48,120 rows)
- Test: `datasets_8494_11879_test_BdBKkAj.csv`

## 🔧 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- LightGBM, XGBoost
- scikit-learn

## 📊 Features Engineered
- Hour, Day, Weekday, Month, Year
- Is_Weekend, Is_Night
- Sine and Cosine transformation of Hour and Month for cyclic behavior

## 📈 EDA Highlights
- Hourly traffic trends per junction
- Weekend vs Weekday vehicle counts
- Monthly traffic distribution

## 🧠 Models Used
1. **LightGBM Regressor** (Best performance)
2. XGBoost Regressor

## 🧪 Evaluation Metrics
- MAE: 2.40
- RMSE: 3.84
- R² Score: 0.96

## 📤 Final Output
Predicted traffic volume (`Vehicles`) for the test data saved as `submission.csv`.

## 📁 Folder Structure
.
├── notebooks/
│   └── smart_city_traffic.ipynb
├── data/
│   ├── train.csv
│   └── test.csv
├── output/
│   └── submission.csv
├── requirements.txt
└── README.md

## 🙏 Acknowledgement
Thanks to [Upscale Campus](https://www.upscalecampus.com) for providing this internship opportunity.