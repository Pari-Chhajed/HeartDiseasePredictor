# ❤️ Heart Disease Predictor
A lightweight, interpretable machine learning model designed to predict the risk of heart disease using routine clinical attributes. Developed using Logistic Regression, this project aims to support early detection in clinical and research settings using publicly available data.

# 📌 Project Description
Cardiovascular disease often develops silently and remains undetected until it becomes critical. This project leverages a clean clinical dataset from Kaggle (Heart Disease UCI dataset) and applies Logistic Regression to build a predictive model that can assist in early-stage risk assessment. The entire process is implemented in Python via Google Colab.

# 📂 Project Structure
 CardioScope.ipynb – Google Colab notebook containing:
  * Data analysis
  * Preprocessing
  * Model training and evaluation
 heart_disease_model.pkl – Saved model using joblib for later use or deployment

# 🧪 Libraries Used

* pandas, nump` – Data manipulation
* matplotlib, seaborn – Visualization
* scikit-learn – Model building and evaluation

# 📈 Model Performance

* Accuracy (Test): **80.5%**
* Precision: **0.77**
* Recall: **0.89**
* F1 Score: **0.82**
* ROC AUC Score: **0.89**
* High recall and AUC make it a strong candidate for early detection use-cases

# 📚 References

* [Heart Disease UCI Dataset – Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
* scikit-learn documentation: [https://scikit-learn.org/stable/](https://scikit-learn.org/stable/)
* Logistic Regression Theory – StatQuest by Josh Starmer
