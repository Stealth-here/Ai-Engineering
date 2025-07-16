# 🏠 House Price Prediction

This project builds a **machine learning model** to predict house prices based on features like area, number of bedrooms, bathrooms, and location. It uses a simple Linear Regression model and includes data preprocessing, exploratory data analysis, and performance evaluation.

---

## 📌 Project Overview

| Feature       | Description                                      |
|---------------|--------------------------------------------------|
| Model         | Linear Regression                                |
| Data          | Simulated dataset (Area, Bedrooms, Location, etc.) |
| Libraries     | pandas, numpy, matplotlib, seaborn, scikit-learn |
| ML Type       | Supervised Learning - Regression                 |
| Input         | House features (numeric + categorical)           |
| Output        | Predicted price of the house                     |

---

## 🧠 Concepts Covered

- One-Hot Encoding for categorical features
- Feature scaling (if needed)
- Train-test split
- Model training and evaluation
- RMSE (Root Mean Squared Error)

---

## 📊 Visualizations

- Price vs Area scatter plot
- Box plots for price distribution by location
- Heatmaps for correlation analysis

---

## 🛠️ How to Run

### Option 1: In Google Colab
- Upload the `.ipynb` notebook and dataset (`train.csv` or similar)
- Run the notebook cell by cell

### Option 2: Locally
```bash
git clone https://github.com/your-username/ai-engineer-roadmap-projects.git
cd ai-engineer-roadmap-projects/02_House_Price_Prediction/
pip install -r requirements.txt
jupyter notebook House_Price_Prediction.ipynb
