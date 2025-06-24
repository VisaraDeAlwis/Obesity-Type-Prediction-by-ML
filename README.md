---

# 🩺 Obesity Prediction Using Machine Learning

![Project Status](https://img.shields.io/badge/status-completed-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

This project focuses on building a predictive machine learning model to classify individuals into various obesity categories based on their lifestyle, physical, and dietary habits. The dataset is sourced from [Kaggle](https://www.kaggle.com/) and contains health and behavioral data of over 2,100 individuals.

---

## 📊 Dataset Overview

* **Source**: Kaggle
* **Size**: 2,111 samples × 17 features
* **Target**: `Obesity` — a categorical label with multiple classes such as `Normal_Weight`, `Overweight_Level_I`, `Obesity_Type_II`, etc.

### Features Include:

* `Age`, `Height`, `Weight`
* `Gender`, `family_history`, `FAVC` (Frequent consumption of high caloric food)
* Physical activity levels: `FAF`, `TUE`
* Daily habits: `SMOKE`, `CH2O`, `SCC`
* Meal patterns: `FCVC`, `NCP`, `CAEC`
* Lifestyle: `CALC`, `MTRANS`

---

## 📌 Objectives

* Preprocess and explore the obesity dataset.
* Visualize relationships between features and obesity levels.
* Build and evaluate a classifier to predict obesity levels.
* Provide insights into which features contribute most to obesity.

---

## 🚀 Technologies Used

* **Python**
* **Pandas**, **NumPy** — Data manipulation
* **Seaborn**, **Matplotlib** — Visualization
* **Scikit-learn** — ML modeling
* **Jupyter Notebook** — Development interface

---

## 📁 Project Structure

```
├── completed_model_1.ipynb     # Notebook with all preprocessing, EDA, modeling
├── Obesity prediction.csv      # Raw dataset
├── README.md                   # Project documentation
```

---

## ✅ Results Summary

The model was trained and evaluated using appropriate classification metrics. Key steps included:

* Label encoding and feature normalization.
* Exploratory Data Analysis (EDA) with heatmaps and pairplots.
* Model selection: logistic regression, random forest, etc.
* Performance evaluation using accuracy, confusion matrix, and classification report.

> 📈 Final Accuracy: 96.5 %
> 🎯 Best Model: XG Boost

---

## 📌 Key Visualizations

* Correlation heatmaps to identify relationships between lifestyle habits and obesity.
* Distribution plots of BMI, food intake, and physical activity.
* Feature importance graph from the best-performing model.

---

## 📦 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/obesity-prediction-ml.git
cd obesity-prediction-ml

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook completed_model_1.ipynb
```

---

## 📚 References

* Dataset from [Kaggle](https://www.kaggle.com/)
* Inspired by real-world health monitoring and behavior analysis problems.

---

## 🤝 Contribution

Feel free to fork this repository, raise issues, or submit PRs. Your feedback is welcome!

---

## 📝 License

This project is licensed under the MIT License.

---

Would you like a custom project cover image or a preview badge to display in your GitHub repo?
