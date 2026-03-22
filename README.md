# 💰 Adult Income Prediction (Census Data)

A professional machine learning implementation using **Object-Oriented Programming (OOP)** to predict whether an individual's income exceeds $50K/year based on census data. This project leverages **Pandas** for data engineering and **Scikit-learn** for predictive modeling.

## 🚀 Key Features
* **Smart Data Management:** Automatically fetches datasets from the UCI Machine Learning Repository and implements local caching for performance.
* **Automated Preprocessing:** Uses `LabelEncoder` to transform categorical text features into model-ready numerical formats.
* **Robust Modeling:** Implements a **Random Forest Classifier** with 100 estimators and `max_depth=10` to ensure generalized learning and prevent overfitting.
* **Balanced Splitting:** Utilizes `stratify` during the train-test split to maintain class proportions, ensuring reliable evaluation metrics.

## 🛠 Tech Stack
* **Language:** Python 3.x
* **Data Manipulation:** Pandas
* **Machine Learning:** Scikit-learn (RandomForest, Train_Test_Split, Preprocessing)

## 📊 Quick Start
1.  **Install Dependencies:**
    ```bash
    pip install pandas scikit-learn
    ```
2.  **Run the Analysis:**
    ```bash
    python Main.py
    ```

## 📈 Model Performance
After training on 80% of the dataset, the model typically achieves:
* **Training Accuracy:** ~88%
* **Testing Accuracy:** ~84-85%

---
**Developed by:** Elyas Nematvand
