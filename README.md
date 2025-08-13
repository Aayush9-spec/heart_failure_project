# 🫀 Heart Health Prediction using Machine Learning

## 📌 Project Overview
This project predicts the likelihood of heart failure based on clinical health records using **Machine Learning**.  
It uses the **Heart Failure Clinical Records Dataset** to train a classification model that can assist in early detection of heart-related health risks.

By applying data preprocessing, exploratory data analysis (EDA), and model training, this project demonstrates how ML can be used in healthcare analytics.


## 📂 Dataset
**Source:** [Heart Failure Clinical Records Dataset](https://www.kaggle.com/datasets/andrewmvd/heart-failure-clinical-data)  
The dataset contains **12 clinical features** and 1 target column (`DEATH_EVENT`) indicating whether the patient died during the follow-up period.

**Features include:**
- `age` — Age of the patient
- `anaemia` — Decrease of red blood cells or hemoglobin (boolean)
- `creatinine_phosphokinase` — Level of CPK enzyme in the blood
- `diabetes` — If the patient has diabetes (boolean)
- `ejection_fraction` — Percentage of blood leaving the heart each time it contracts
- `high_blood_pressure` — If the patient has hypertension (boolean)
- `platelets` — Platelets in the blood
- `serum_creatinine` — Level of serum creatinine in the blood
- `serum_sodium` — Level of serum sodium in the blood
- `sex` — Woman or man (binary: 0 = female, 1 = male)
- `smoking` — If the patient smokes (boolean)
- `time` — Follow-up period (days)
- **Target:** `DEATH_EVENT` — 1 = patient died, 0 = patient survived


## ⚙️ Installation

1. **Clone this repository**

git clone https://github.com/yourusername/ml-heart-health.git
cd ml-heart-health


2. **Create and activate a virtual environment** (optional but recommended)


python -m venv venv
source venv/bin/activate  # for Linux/Mac
venv\Scripts\activate     # for Windows


3. **Install dependencies**


pip install -r requirements.txt


*(If `requirements.txt` is missing, manually install: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`.)*


## 🚀 Usage

1. **Run the main script**

python main.py


2. **Modify parameters** inside `main.py` to:

   * Change the ML model
   * Adjust preprocessing steps
   * Tune hyperparameters

---

## 🧠 Model Pipeline

* **Data Loading & Cleaning** — Load dataset, handle missing values, and remove duplicates.
* **Exploratory Data Analysis (EDA)** — Understand feature distributions and relationships.
* **Feature Scaling** — Normalize features for better model performance.
* **Model Training** — Trains a classification model (Logistic Regression / Random Forest / etc.).
* **Evaluation** — Accuracy, confusion matrix, precision, recall, and F1-score.

---

## 📊 Example Output

*(Replace with actual screenshot if available)*
![Example Confusion Matrix](docs/confusion_matrix.png)

---

## 📜 License

This project is licensed under the MIT License — you are free to use, modify, and distribute with attribution.

---

## 👨‍💻 Author

**Aayush Kumar Singh**
B.Tech CSE, PSIT Kanpur
Passionate about AI, Machine Learning, and Data Science.

