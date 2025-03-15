# Forest Fire Prediction

## 📌 Project Overview
This project aims to analyze and predict forest fire occurrences based on environmental and meteorological factors. Using machine learning techniques, we develop a predictive model to estimate the burned area of forest fires. The dataset contains historical fire records with attributes such as temperature, wind speed, humidity, and drought indices. The goal is to enhance early warning systems and improve forest fire management by providing data-driven insights.

## 📂 Dataset
- The dataset consists of historical forest fire incidents with features influencing fire behavior.
- Key features include:
   1. X - x-axis spatial coordinate within the Montesinho park map: 1 to 9
   2. Y - y-axis spatial coordinate within the Montesinho park map: 2 to 9
   3. month - month of the year: "jan" to "dec" 
   4. day - day of the week: "mon" to "sun"
   5. FFMC - FFMC index from the FWI system: 18.7 to 96.20
   6. DMC - DMC index from the FWI system: 1.1 to 291.3 
   7. DC - DC index from the FWI system: 7.9 to 860.6 
   8. ISI - ISI index from the FWI system: 0.0 to 56.10
   9. temp - temperature in Celsius degrees: 2.2 to 33.30
   10. RH - relative humidity in %: 15.0 to 100
   11. wind - wind speed in km/h: 0.40 to 9.40 
   12. rain - outside rain in mm/m2 : 0.0 to 6.4 
   13. area - the burned area of the forest (in ha): 0.00 to 1090.84 
   (this output variable is very skewed towards 0.0, thus it may make
    sense to model with the logarithm transform). 

## 🔧 Technologies Used
- **Programming Language**: Python
- **Libraries**: NumPy, Pandas, Matplotlib, Scikit-learn
- **Machine Learning Techniques**: Linear Regression

## 🚀 Project Workflow
1. **Data Preprocessing**: feature engineering.
2. **Exploratory Data Analysis (EDA)**: Understanding data distribution and correlations.
3. **Model Training & Evaluation**: Training machine learning models and evaluating their performance.
4. **Prediction & Visualization**: Visualizing actual vs predicted fire spread.

## 📊 Model Evaluation Metrics
- **Root Mean Square Error (RMSE)**

## 📎 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/NTKhoii/ForestFirePrediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python script to train the model.

## 🔥 Results & Insights
- The model helps predict the burned area based on environmental conditions.
- Visualization of actual vs predicted values provides insights into model performance.

## 📌 Future Improvements
- Implement deep learning models (e.g., Neural Networks).
- Incorporate real-time weather data for better predictions.
- Optimize feature selection and hyperparameter tuning.

## 📜 License
This project is open-source and available under the **MIT License**.

---
💡 **Contributions are welcome!** Feel free to open issues or submit pull requests to improve the project.
