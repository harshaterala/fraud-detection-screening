# Fraud Detection - Screening Project

This repository contains an end-to-end fraud detection pipeline developed as part of a technical screening task.  
The project analyzes highly imbalanced financial transaction data and applies multiple machine learning models to detect fraudulent transactions.

## 📌 Features
- Data cleaning, preprocessing, and feature engineering.
- Handling extreme class imbalance.
- Training & evaluating:
  - Logistic Regression
  - Random Forest
  - XGBoost
- SHAP explainability for model interpretability.
- Visualizations for class distribution, feature importance, and ROC curves.

## 📊 Results
| Model               | Precision (Fraud) | Recall (Fraud) | ROC AUC |
|---------------------|-------------------|----------------|---------|
| Logistic Regression | 0.02              | 0.98           | 0.968   |
| Random Forest       | 0.71              | 0.88           | 0.938   |
| XGBoost             | 0.39              | 0.93           | 0.966   |

**Key Insight:** Random Forest achieved the best balance between precision and recall for fraud detection, with ROC AUC ≈ 0.97.

## 🛠 Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, XGBoost, SHAP, imbalanced-learn
- **Platform:** Google Colab

## 📂 File Structure

Fraud_Detection_Screening_Project.ipynb # Jupyter notebook with full pipeline
README.md # Project documentation
requirements.txt # Python dependencies

bash
Copy
Edit

## 📦 Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/<your-username>/fraud-detection-screening.git
cd fraud-detection-screening
pip install -r requirements.txt
🚀 Usage
Run the notebook:

bash
Copy
Edit
jupyter notebook Fraud_Detection_Screening_Project.ipynb
Or open it directly in Google Colab.

📈 Future Improvements
Hyperparameter tuning with Optuna.

Ensemble models for better precision.

Real-time fraud alert pipeline.

📄 License
This project is open-source and available under the MIT License.

yaml
Copy
Edit

---

### **requirements.txt**
```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
shap
imbalanced-learn
Next Steps to Push
Save the above README.md and requirements.txt in the same folder as your notebook.

Run:

bash
Copy
Edit
git add README.md requirements.txt
git commit -m "Add README and requirements"
git push
