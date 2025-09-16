# 🏠 Housing-ML-Pipeline

An **end-to-end Machine Learning pipeline** built on housing data.  
This project takes raw CSV data → preprocesses it → trains multiple ML models → evaluates them → persists the best model → and runs batch predictions on new data.  

It’s designed for **reproducibility, simplicity, and real-world deployment readiness**.

---

## 🚀 Features
- Automated **data ingestion** from CSV  
- **Preprocessing & cleaning** (missing values, encoding, scaling)  
- Training **multiple ML algorithms** (e.g., Linear Regression, Random Forest, etc.)  
- **Evaluation & selection** of best model (based on MAE/RMSE/R²)  
- **Model persistence** with Pickle  
- **Batch inference** from `input.csv` → `output.csv`  

---

## 📂 Project Structure
ml-pipeline-housing/
│

├── data/

│   ├── input.csv

│   ├── output.csv

│   └── housing.csv



├── models/

│   └── model.pkl


├── notebooks/

│   └── exploration



├── src/

│   ├── 01_main_training_ML_algos.py

│   ├── 02_main_model_persistence.py



├── README.md



---

## ⚙️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Housing-ML-Pipeline.git
   cd Housing-ML-Pipeline




