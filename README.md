# 🌧️ Cloudburst Prediction System

A machine learning project designed to **predict cloudbursts** using weather data and classification algorithms. The system applies **data preprocessing, visualization, and multiple ML models** to analyze patterns and improve accuracy.

---

## 🚀 Features
- 📊 Data preprocessing and cleaning of meteorological datasets.  
- 🔍 Exploratory Data Analysis (EDA) with insightful visualizations.  
- 🤖 Multiple ML algorithms trained:  
  - Logistic Regression  
  - Naive Bayes  
  - Random Forest  
  - Support Vector Machine (SVM)  
- 💾 Pre-trained models saved as `.pkl` for reuse.  
- 🖥️ Deployment-ready notebook (`Model_Deployment.ipynb`).  
- 📈 Comparative model evaluation for accuracy and performance.  

---

## 🛠️ Technologies Used
- **Python (3.x)** – Core programming language.  
- **Pandas, NumPy** – Data preprocessing & manipulation.  
- **Matplotlib, Seaborn** – Data visualization.  
- **Scikit-learn** – ML algorithms & model evaluation.  
- **Jupyter Notebook** – Experimentation & documentation.  
- **Pickle** – Saving and loading trained models.  

---

## 📂 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/jain-ati/Cloudburst_Prediction_System.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd Cloudburst_Prediction_System
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
   Open and explore notebooks like:
   - `CloudBurst_Prediction.ipynb`  
   - `Data_Visualization.ipynb`  
   - `Model_Deployment.ipynb`  

---

## 📊 Dataset
- File: **`Dataset.csv`**  
- Contains meteorological attributes used for training and testing.  
- Preprocessing steps handle missing values, normalization, and feature selection.  

---

## 📦 Pre-trained Models
Trained ML models are saved as `.pkl` files:  
- `CBT_LR_TD.pkl` → Logistic Regression  
- `CBT_NB_TD.pkl` → Naive Bayes  
- `CBT_RF_TD.pkl` → Random Forest  
- `CBT_SVM_TD.pkl` → Support Vector Machine  

You can directly load these models to make predictions without retraining.  

---

## 🙋‍♀️ Author
**Anshika Jain**  
Made with ❤️ to learn and explore **Machine Learning, Data Science, and Model Deployment**.  

GitHub Repository:  
[Cloudburst Prediction System](https://github.com/jain-ati/Cloudburst_Prediction_System.git)  
