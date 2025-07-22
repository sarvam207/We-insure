# WeInsure – Medical Insurance Cost Prediction 💡

An interactive machine learning project to predict medical insurance charges based on user input features like age, BMI, region, and smoking status.

## 🔍 Overview
This project explores the factors that influence insurance pricing and builds regression models to predict individual insurance costs. It includes an interactive Jupyter Notebook interface using `ipywidgets` for real-time predictions.

## 📊 Dataset
The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance) and includes 7 features:
- Age
- Sex
- BMI
- Children
- Smoker
- Region
- Charges (target)

## 🧠 ML Models Used
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

## 🛠️ Features
- Exploratory Data Analysis (EDA)
- Data preprocessing and encoding
- Model training and evaluation (R², MAE, RMSE)
- Interactive prediction using `ipywidgets`
- Feature importance visualization

## 💡 Key Insights
- Smoking status and BMI are the most influential factors.
- Tree-based models (XGBoost) performed best on evaluation metrics.

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/weinsure-insurance-prediction.git
   cd weinsure-insurance-prediction
```
2. Install dependencies:
pip install -r requirements.txt


3. Open the notebook:
jupyter notebook weinsure_prediction.ipynb


4. Use the widgets to test predictions interactively.



📦 Requirements

pandas
numpy
seaborn
matplotlib
scikit-learn
xgboost
ipywidgets


📁 Project Structure

weinsure/
├── weinsure_prediction.ipynb
├── insurance.csv
├── README.md
└── requirements.txt

📬 Contact

For queries or collaborations, feel free to connect!
Sarvam