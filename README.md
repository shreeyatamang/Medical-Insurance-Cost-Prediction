# 🏥 Medical Insurance Cost Prediction

This project predicts **insurance charges** using **Linear Regression** based on health and demographic factors. It demonstrates a complete ML workflow from **data preprocessing** to **model evaluation**.

---

## 📊 Workflow
1. **Insurance Cost Data** → Collect the dataset (`insurance.csv`)
2. **Data Analysis** → Understand features (age, sex, bmi, children, smoker, region, charges)
3. **Data Preprocessing** → Handle missing values, encode categorical data, and scale features
4. **Train-Test Split** → Split data into training and testing sets
5. **Model Training** → Train a Linear Regression model
6. **Prediction** → Predict insurance cost for new data

---

## 🚀 Tech Stack
- Python 🐍  
- Pandas, NumPy (Data handling)  
- Matplotlib, Seaborn (Visualization)  
- Scikit-learn (ML model & evaluation)  

---

## 📂 Dataset
The dataset used: `insurance.csv`  
- `age`: Age of primary beneficiary  
- `sex`: Gender (male/female)  
- `bmi`: Body Mass Index  
- `children`: Number of children covered by insurance  
- `smoker`: Smoking status  
- `region`: Residential area (northeast, northwest, southeast, southwest)  
- `charges`: Medical insurance cost (target variable)  

---

## 📈 Results
- Model: Linear Regression  
- Output: Predicted insurance cost (USD)  
- Example Prediction:  
  ```python
  Input: (age=31, sex=male, bmi=25.7, children=0, smoker=yes, region=northwest)
  Output: Insurance cost ≈ $3760
