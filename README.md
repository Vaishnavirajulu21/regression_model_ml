# 🚗 Car Price Prediction using Linear Regression

This project predicts car prices using a **Linear Regression model**.  
The workflow includes data preprocessing, training, evaluation, and visualization.  

---

## 🔹 Steps Followed
1. **Load Dataset** (`automobile.csv`)  
2. **Handle Missing Values**  
   - Filled numerical columns with mean  
   - Filled categorical columns with mode  
3. **Preprocessing**  
   - One-hot encoding for categorical features  
   - Split data into train (80%) and test (20%)  
4. **Model Training**  
   - Linear Regression model fitted on training data  
5. **Model Evaluation**  
   - Metrics: MAE, MSE, R²  
   - Cross-validation scores  
6. **Visualization**  
   - Actual vs Predicted Prices  
   - Residual Plot  
   - Distribution plots for actual vs predicted values  

---

## ⚙️ Requirements
```bash
pip install pandas numpy scikit-learn matplotlib seaborn


📊 Example Output
MAE: 2150.34
MSE: 8564237.12
R²: 0.86


👩‍💻 Author: Vaishnavi V

