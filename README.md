# 📊 Customer Segmentation

This project clusters mall customers based on their salary and spending score.  
It applies **Machine Learning models** such as **KMeans** and **DBSCAN**, using scalling models like **StandardScaler**.

---

## 🚀 Project Workflow
1. **Data Exploration & Cleaning**  
   - Checked data types, missing values, and unique values.  

2. **Feature Preparation**  
   - Scaled features before training the models.

3. **Model Training**  
   - **KMeans** (baseline model).  
   - **DBSCAN** (advanced model).  

4. **Evaluation Metrics**  
   - Precision, Recall, and F1-Score.  
   - Cross-validation for consistency.  
   - Compared models accuracy scores through a bar plot.  

---

## 🤖 Models Trained
- **KMeans** → Produced clear, balanced clusters (better interpretability).
- **DBSCAN** → Captured outliers, but struggled with defining well-separated clusters in this dataset.

🏆 **Conclusion:**
KMeans performed best for customer segmentation, providing reliable and business-friendly groupings.

---

## 📦 Dataset
- Mall Customer (Kaggle)

---

## 🛠️ Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Matplotlib
- scikit-learn  

---

## 📂 Project Structure
customer-segmentation/

│── data/

│     └── Mall_Customers.csv       # Original dataset

│

│── notebooks/

│     └── customer_segmentation.ipynb  # Jupyter Notebook with full workflow

│

│── README.md                           # Project documentation

│── requirements.txt                    # Python dependencies

│── .gitignore                          # Ignore unnecessary files

│── LICENSE                             # License file
