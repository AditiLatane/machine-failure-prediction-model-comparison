# ⚙️ Machine Failure Prediction — Model Comparison

## 📑 Table of Contents

- [About the Project](#-about-the-project)
- [Project Objectives](#-project-objectives)
- [Technologies Used](#️-technologies-used)
- [Project Workflow](#-project-workflow)
- [Model Comparison](#-model-comparison)
- [Key Learnings](#-key-learnings)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

## 📌 About the Project

This project uses machine learning to predict whether a machine is likely to fail based on its sensor readings, such as temperature, pressure, vibration, and power consumption.

I compared four machine learning models to identify which one performs best at predicting machine failures.

## 🎯 Project Objectives

- Understand machine sensor data through visualizations and analysis.
- Handle imbalanced failure and non-failure records using SMOTE.
- Train and compare four machine learning models.
- Identify important factors associated with machine failures.
- Predict machine failures and save the best-performing model.

## 🛠️ Technologies Used

- **Python** — Programming
- **Pandas & NumPy** — Data analysis
- **Matplotlib & Seaborn** — Data visualization
- **Scikit-learn** — Machine learning
- **Imbalanced-learn** — Handling imbalanced data

## 🔍 Project Workflow

1. **Data Loading:** Import libraries and load the dataset.
2. **Exploratory Data Analysis (EDA):** Examine the data, missing values, duplicates, sensor readings, and relationships between features.
3. **Data Preparation:** Split the data into training and testing sets and analyze class imbalance using SMOTE.
4. **Model Training:** Train four machine learning models:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Gradient Boosting
5. **Model Comparison:** Compare model performance using accuracy, precision, recall, and F1-score.
6. **Feature Importance:** Identify which sensor readings contribute most to predictions.
7. **Failure Prediction:** Create a function to predict whether a machine will fail.
8. **Model Saving:** Save the selected model for future predictions.

## 📊 Model Comparison

  ![Model Comparison](assets/model_comparison.png)



## 📊 Feature Importance

  ![Feature Importance](assets/feature_importance.png)



## 💡 Key Learnings

- Analyzing and visualizing real-world-style sensor data.
- Training and comparing different machine learning models.
- Understanding how to evaluate prediction performance.
- Identifying important factors related to machine failures.
- Building and saving a reusable prediction model.

## 🚀 Future Improvements

- Build an interactive dashboard for machine failure predictions.
- Explore how the model could support preventive maintenance.

## 👩‍💻 Author

**Aditi Latane**

- GitHub: [AditiLatane](https://github.com/AditiLatane)
- Portfolio: [Data Analyst Portfolio](https://aditi-latane-data-analyst-portfolio.vercel.app/)

---

⭐ If you find this project useful, consider giving the repository a star!
