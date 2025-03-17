# Airplane Accident Prediction Project

## 🚀 Overview

This project aims to predict airplane accident risks using machine learning techniques, focusing on improving aviation safety by identifying risk factors associated with accidents. The predictive model will help stakeholders understand critical factors leading to aviation incidents and accidents, thereby enhancing safety measures and preventive actions.

---

## 📚 Dataset Overview

The dataset used in this project consists of a balanced mix of numerical and categorical features, meeting the requirement of at least 10 columns. Key features include:

- Aircraft Make and Model
- Number of Engines
- Federal Aviation Regulations (FAR)
- Safety Recommendations
- Geographical Data (Country, State, City)
- Weather Conditions

The dataset can be accessed from the following source:
- [CAROL Query](https://data.ntsb.gov/carol-main-public/basic-search)

---

## 🛠️ Project Workflow

The workflow for this project includes the following steps:

1. **Data Loading and Preprocessing**: Cleaning and transforming data for model readiness.
2. **Exploratory Data Analysis (EDA)**: Understanding data distributions, relationships, and identifying key insights.
3. **Feature Engineering**: Preparing data through encoding categorical features, splitting into training and test sets.
4. **Modeling**: Implementing multiple supervised learning algorithms:
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM)
   - Logistic Regression
   - Boosting Techniques
4. **Model Evaluation and Tuning**: Employing cross-validation and hyperparameter tuning to select the best-performing model.
5. **Model Deployment**: Deploying the best model as an interactive web application using Streamlit.

---

## 🚀 Running the Application

To run the Streamlit application locally, follow these steps:

1. Clone the repository:
```bash
git clone [repository-url]
cd your-repository-folder
```

2. Install required libraries:
```bash
pip install -r requirements.txt
```

3. Start the Streamlit app:
```bash
streamlit run deployment/app.py
```

---

## 📁 Repository Structure

```
Airplane-Accident-Prediction/
├── deployment/
│   ├── app.py
│   ├── eda.py
│   ├── prediction.py
│   └── model.pkl
├── Airplane Accident Clean.csv
├── milestone_classification.ipynb
├── milestone_classification_inference.ipynb
└── README.md
```

---

## 🎯 Intended Users

This application is designed primarily for:
- Aviation safety analysts
- Airline companies
- Regulatory bodies overseeing aviation safety
- General aviation stakeholders interested in predictive risk assessment

---

## 📥 Dataset Source

The dataset was sourced from [US Government](https://data.ntsb.gov/carol-main-public/basic-search), specifically selected for its comprehensive details regarding airplane incidents and accidents.

---

## 📌 Future Improvements

Future improvements for this project include:
- Incorporating real-time aviation data for dynamic predictions.
- Utilizing advanced techniques such as deep learning or ensemble methods to enhance accuracy.
- Integrating geospatial analytics for better location-based insights.

---

## 📑 Conclusion

This project highlights the power of machine learning in predicting aviation risks, aiming to improve preventive measures and enhance overall aviation safety.

