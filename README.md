# ✈️ Flight Fare Prediction

> Predicting airline ticket prices using Python and Machine Learning.

## 📁 Dataset
- Source: [Kaggle – Flight Fare Prediction](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)
- Description: Contains data such as airline, source, destination, total stops, duration, and price.

## 🎯 Objective
To build a machine learning model that can predict flight ticket prices based on travel details such as airline, duration, stops, and more.

## 🛠️ Tools & Libraries
- Python
- pandas, NumPy
- matplotlib, seaborn
- scikit-learn
- Jupyter Notebook

## 🚀 Process
1. **Data Cleaning**  
   - Handled missing values  
   - Converted categorical features using label/one-hot encoding  
   - Converted duration into numerical format  

2. **EDA**  
   - Visualized relationships between price and features like airline, stops, duration  
   - Checked for outliers and feature importance

3. **Feature Engineering**  
   - Extracted day, month from the date column  
   - Converted duration to minutes  

4. **Model Building**  
   - Tried multiple regression models (Linear Regression, Random Forest, etc.)  
   - Evaluated using RMSE and R²

## 📈 Key Findings
- Airlines and total stops significantly affect ticket prices  
- Duration and journey time also impact prices  
- Random Forest performed better than Linear Regression in this case

## 📌 How to Run
```bash
git clone https://github.com/AiSkwArYa-2003/flightfare-predict.git
