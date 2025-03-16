# Customer Spending Prediction

## 📌 Project Overview
This project applies machine learning to predict customer spending behavior using a preprocessed dataset. The models used include:
- **Random Forest**

The final model helps in understanding key factors that influence customer spending and provides actionable insights.

---
## 📂 Repository Structure
```
📁 Customer-Spending-Prediction/
│── 📁 data/                # Contains the original and processed datasets
│    ├── final_dataset_ready_group1.csv
│ 
│
│── 📁 models/              # Contains saved machine learning models
│    ├── random_forest_model.pkl
│ 
│
│      
│
│
│── customer_spending_analysis.ipynb            # Notebooks used for data preprocessing and modeling
│── README.md               # Project documentation
```

---
## 🚀 How to Run the Project
### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/yourusername/Customer-Spending-Prediction.git
cd Customer-Spending-Prediction
```

### 2️⃣ **Install Required Dependencies**
Make sure you have Python installed, then run:
```bash
pip install -r requirements.txt
```

# Make predictions
y_pred = model.predict(X_test)
print(y_pred[:5])
```

