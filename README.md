# Health Insurance Cost Prediction  

## 📌 Project Overview  
This project focuses on analyzing a **health insurance dataset** to explore factors affecting medical costs and predict insurance charges using **machine learning models**. The dataset includes variables such as age, BMI, smoking status, and region to understand their impact on medical expenses.  

## 📊 Tasks Covered  
### **1️⃣ Data Exploration**  
- Load and inspect dataset structure.  
- Identify missing values and variable distributions.  
- Compute key statistics (mean, median, standard deviation).  

### **2️⃣ Data Visualization**  
- **Histograms & Boxplots** to analyze variable distributions.  
- **Scatter plots & Correlation matrices** to explore relationships.  

### **3️⃣ Machine Learning Models**  
We evaluate three machine learning models:  
- **Linear Regression**  
- **Random Forest Regressor**  
- **Support Vector Regressor (SVR)**  
Each model is trained and evaluated using **Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score**.  

### **4️⃣ Key Findings**  
- **Random Forest** achieved the best performance with an **R² Score of 0.87**.  
- **Linear Regression** performed reasonably well (**R² = 0.78**), but lacked flexibility for complex patterns.  
- **SVR** struggled with this dataset, achieving a low **R² Score of 0.05**.  

## 🚀 Tech Stack  
- **Python**  
- **Pandas, NumPy** (Data Handling)  
- **Matplotlib, Seaborn** (Data Visualization)  
- **Scikit-Learn** (Machine Learning)  

## 📈 Results & Discussion

The Random Forest model provides the most accurate predictions, suggesting non-linear interactions among variables like BMI, smoking status, and age significantly influence medical costs.



