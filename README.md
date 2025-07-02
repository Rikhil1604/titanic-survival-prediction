As someone new to Machine Learning, I wanted a project that would help me apply what I’ve learned, explore real-world data, and get hands-on with the entire data science workflow. The Titanic dataset is perfect for beginners like me — it’s small, well-documented, and teaches you everything from data cleaning and visualization to building models and making predictions. If you're a beginner too, following this project step-by-step will give you the confidence to take on bigger challenges and enter your first Kaggle competition! 

This project helped me understand how ML works in practice, not just in theory. If you're a beginner too, following this project step-by-step will give you the confidence to take on bigger challenges and even enter your first Kaggle competition!


🚢 Titanic Survival Prediction | Kaggle Mini Project

A complete machine learning project using the classic Titanic dataset from Kaggle. This repo walks through the full pipeline: data exploration, cleaning, feature engineering, model building, and evaluation — ending with a prediction submission.

---

📊 Problem Statement

> Can you build a machine learning model that predicts which passengers survived the Titanic shipwreck?

This project aims to solve that using supervised classification techniques.

---

🗂️ Project Structure
titanic-survival-prediction/
├── data/ # Dataset files (train/test CSVs from Kaggle)
├── notebooks/ # Jupyter Notebooks for EDA and modeling
├── output/ # Generated predictions for Kaggle
├── requirements.txt # Python package dependencies
├── README.md # Project overview (this file)


---
🔧 Tools & Libraries

- Python 3.10
- NumPy, Pandas
- Seaborn, Matplotlib
- Scikit-learn
- Jupyter Notebook 6.5.4(stable)

---

🔍 Workflow

1. **Load & Inspect Data**
   - Check for missing values
   - Understand data types and distributions

2. **Exploratory Data Analysis**
   - Visualize survival rates by class, gender, age
   - Plot missing values, distributions, and correlations

3. **Data Cleaning & Feature Engineering**
   - Impute missing values (Age, Embarked)
   - Drop irrelevant features (Cabin, Ticket, Name)
   - Convert categorical to numeric using one-hot encoding

4. **Model Building**
   - Logistic Regression (baseline model)
     
5. **Model Evaluation**
   - Accuracy score
   - Confusion matrix
  
6. **Prediction & Submission**
   - Predict on the test set
   - Export CSV for Kaggle

---

📈 Results

Achieved an accuracy of ~80% using just Logistic Regression with basic feature engineering.

---

📁 Dataset

📥 Download from Kaggle:  
👉 [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)

---

📦 Installation

To run this project locally:

```bash
git clone https://github.com/Rikhil1604/titanic-survival-prediction.git
cd titanic-survival-prediction
pip install -r requirements.txt
