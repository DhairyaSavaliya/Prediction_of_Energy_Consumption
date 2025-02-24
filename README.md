

## **Prediction of Energy Consumption** ⚡📊  

This project aims to predict **energy consumption** using various **machine learning models**, including **Linear Regression, Random Forest, Gradient Boosting, AdaBoost, XGBoost, and SVM**. The dataset contains historical energy consumption data with multiple influencing factors such as **temperature, HVAC usage, lighting usage, and holidays**.

---

### **📌 Features of the Project**
- 📌 **Data Cleaning & Preprocessing**: Handling missing values, converting categorical data, and feature engineering.  
- 📌 **Feature Selection**: Identifying the most relevant features for better model performance.  
- 📌 **Machine Learning Models**: Training and evaluating different models to compare their effectiveness.  
- 📌 **Performance Metrics**: Using **Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), R² Score, and Mean Absolute Percentage Error (MAPE)**.  
- 📌 **Visualization**: Comparing model performance using **bar charts**.  

---

### **🔧 Tech Stack**
- **Python** 🐍  
- **Pandas, NumPy** for data manipulation  
- **Seaborn, Matplotlib** for visualization  
- **Scikit-Learn, XGBoost** for machine learning models  

---

### **📂 Dataset**
The dataset used for this project can be found here:  
📌 **[Energy Consumption Dataset]([<INSERT_DATASET_LINK_HERE>](https://www.kaggle.com/datasets/mrsimple07/energy-consumption-prediction/data))**  


---

### **🚀 How to Run the Project**
1. **Clone the Repository**  
   ```sh
   git clone https://github.com/DhairyaSavaliya/Prediction_of_Energy_Consumption.git
   cd Prediction_of_Energy_Consumption
   ```

2. **Install Dependencies**  
   ```sh
   pip install -r requirements.txt
   ```

3. **Download the Dataset**  
   - Place the dataset file (`Energy_consumption.csv`) inside the project folder.

4. **Run the Script**  
   ```sh
   python energy_consumption.py
   ```

---

### **📊 Model Performance Comparison**
After training, the models are compared based on various metrics using **a grouped bar chart** for better visualization.

---

### **📂 Project Structure**
```
📦 Energy_Consumption_Prediction
├── 📄 energy_consumption.py   # Main script for training and evaluation
├── 📄 dataset.csv             # Dataset file
├── 📄 requirements.txt        # Dependencies
├── 📄 README.md               # Project documentation
└── 📁 models                  # Saved models (if applicable)
```

---

### **📌 Results & Observations**
- **Random Forest & Gradient Boosting** performed the best with lower RMSE.  
- **Linear Regression & SVM** had relatively higher errors.  
- Feature engineering significantly impacted the model performance.  

---

### **🛠️ Future Improvements**
- ✅ Hyperparameter tuning for better model optimization.  
- ✅ Deployment using **Flask/FastAPI** for real-time predictions.  
- ✅ Adding **deep learning models (LSTM/ANNs)** for time-series forecasting.  

---

### **👨‍💻 Author**
- **Dhairya Savaliya**  
- 📧 Contact: [Your Email]  
- 🌐 GitHub: [DhairyaSavaliya](https://github.com/DhairyaSavaliya)  

🚀 *Feel free to contribute, suggest improvements, or fork the repository!*  
