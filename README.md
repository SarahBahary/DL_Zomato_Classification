
## 🍽️ Zomato Restaurant Success Classification using Deep Learning

This project applies **deep learning techniques** to predict the success or failure of restaurants listed on the Zomato platform. Leveraging real-world features like online ordering availability, table booking, ratings, cuisine types, and more, the model aims to support informed decision-making in the food and hospitality domain.

---

### ✅ Project Objectives

* 📊 **Data Exploration & Preprocessing**: Clean and encode features from the Zomato dataset (e.g., `rate`, `votes`, `location`, `cuisines`, etc.).
* 🧠 **Deep Learning Model Development**: Train and evaluate a neural network to classify restaurants based on their likelihood of success.
* 📈 **Performance Evaluation**: Assess model accuracy, loss, confusion matrix, and other metrics to validate effectiveness.
* 🧹 **Handle Imbalanced Classes**: Apply strategies like class weighting or resampling to balance success/failure labels.

---

### 🔍 Dataset Overview

The dataset contains restaurant-level features such as:

* `online_order`, `book_table` (binary services)
* `rate` (user rating)
* `votes`, `approx_cost(for two people)`
* `cuisines`, `menu_item`, `listed_in(city)`, and more

The **target label** is binary, indicating whether the restaurant is successful or not (based on rating, votes, or business rules).

---

### 🧠 Technologies Used

* **Python 3**
* **Pandas, NumPy, Matplotlib, Seaborn** – Data analysis & visualization
* **TensorFlow / Keras** – Deep learning model implementation
* **Scikit-learn** – Preprocessing, evaluation metrics, and train/test splitting

---

### 🛠️ Project Workflow

1. **Data Cleaning & Encoding**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Engineering**
4. **Model Building (ANN)**
5. **Training, Evaluation, and Tuning**
6. **Prediction & Insight Extraction**

---

### 📊 Sample Results

* **Accuracy**: *\[Insert Accuracy]*
* **Loss**: *\[Insert Loss]*
* **Confusion Matrix**: *\[Image or description]*
* **Model Insights**: Which features most influence success

---

### 📌 Future Improvements

* Add support for other ML models (e.g., XGBoost, SVM)
* Integrate real-time data scraping from Zomato APIs
* Deploy the model as a web app using Flask or Streamlit

---
