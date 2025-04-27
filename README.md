# Medical Insurance Cost Prediction 

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Regression-informational)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)


This project builds a **machine learning model** to predict **medical insurance charges** based on personal information such as age, gender, BMI, number of children, smoking habits, and region.

The project involves **data preprocessing**, **exploratory data analysis (EDA)**, **model training**, and **evaluation**.

---

## 📂 Project Structure

- `Medical_Insurance_Cost_Prediction.ipynb`: Jupyter Notebook containing the full workflow – from data analysis to model building and evaluation.
- `insurance.csv`: Dataset containing demographic and insurance-related information.

---

## 🗃️ Dataset Overview

The dataset (`insurance.csv`) includes the following columns:

| Column Name | Description |
|:------------|:------------|
| `age` | Age of the individual |
| `sex` | Gender (male/female) |
| `bmi` | Body Mass Index |
| `children` | Number of children/dependents |
| `smoker` | Smoking status (yes/no) |
| `region` | Residential region (northeast, southeast, southwest, northwest) |
| `charges` | Insurance charges (target variable) |

---

## 🔎 Project Highlights

- **Data Cleaning:** 
  - Checked for missing values.
  - Encoded categorical features (`sex`, `smoker`, `region`).

- **EDA (Exploratory Data Analysis):** 
  - Visualized distributions and relationships.
  - Identified key features influencing insurance charges (e.g., smoking status, BMI, age).

- **Feature Engineering:**
  - Used label encoding/one-hot encoding where appropriate.

- **Model Building:**
  - Trained models like **Linear Regression**, **Random Forest Regressor**, etc.
  - Evaluated performance using metrics like **Mean Absolute Error (MAE)**, **R² Score**, and **Root Mean Squared Error (RMSE)**.

- **Model Optimization:** 
  - Compared multiple models and fine-tuned hyperparameters where needed.

---

## 📊 Results

- Achieved good predictive performance, with R² score 0.85.
- Found **smoking status**, **BMI**, and **age** to be the most significant factors influencing insurance charges.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/CraigDaGama/Medical-Insurance-Cost-Prediction.git
   cd Medical_Insurance_Cost_Prediction
   ```

2. Install dependencies (preferably in a virtual environment):
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```bash
   jupyter notebook Medical_Insurance_Cost_Prediction.ipynb
   ```

4. Run all cells to reproduce the analysis and predictions.

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---


## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---
