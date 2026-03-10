#  Mobile Price Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

A Machine Learning project that predicts the **price category of mobile phones** based on their hardware specifications such as RAM, battery capacity, camera quality, and screen resolution.

The model classifies mobile phones into four price categories:

* **0 → Low Cost**
* **1 → Medium Cost**
* **2 → High Cost**
* **3 → Very High Cost**

---

#  Project Overview

The goal of this project is to build a **classification model** that predicts mobile phone price range using market mobile specifications.

This project demonstrates the **complete machine learning workflow**:

1. Data Loading
2. Data Exploration (EDA)
3. Data Preprocessing
4. Feature Selection
5. Model Training
6. Model Evaluation
7. Prediction

---

#  Dataset Features

| Feature       | Description              |
| ------------- | ------------------------ |
| battery_power | Battery capacity (mAh)   |
| blue          | Bluetooth support        |
| clock_speed   | Processor speed          |
| dual_sim      | Dual SIM support         |
| fc            | Front camera megapixels  |
| four_g        | 4G support               |
| int_memory    | Internal storage         |
| mobile_wt     | Mobile weight            |
| n_cores       | Number of CPU cores      |
| pc            | Primary camera           |
| px_height     | Screen resolution height |
| px_width      | Screen resolution width  |
| ram           | RAM size                 |
| sc_h          | Screen height            |
| sc_w          | Screen width             |
| talk_time     | Battery talk time        |
| three_g       | 3G support               |
| touch_screen  | Touch screen support     |
| wifi          | WiFi support             |

Target Variable:

**price_range**

---

#  Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-Learn**
* **Google Colab**

---

#  Machine Learning Models

The following models were implemented and evaluated:

* Logistic Regression
* Decision Tree
* Random Forest Classifier

 **Best Model:** Random Forest
 **Accuracy Achieved:** ~97%

---

#  Data Visualization

Exploratory Data Analysis included:

* Correlation Heatmap
* Feature Distribution
* Price Range Analysis
* Feature Importance

These visualizations helped identify the most important factors affecting mobile phone price.

Key influential features:

* RAM
* Battery Power
* Pixel Resolution
* Internal Memory

---

#  Project Workflow

```
Data Collection
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Prediction
```

---

#  Key Insights

* **RAM is the most important factor** influencing mobile price.
* Higher **battery power and screen resolution** also increase price category.
* Machine learning can effectively classify smartphone pricing segments.

---

#  Repository Structure

```
mobile-price-prediction-ml
│
├── mobliepricepredication.ipynb
├── dataset.csv
├── README.md
├── .gitignore
├── LICENSE 
```

---

# 🏁 How to Run This Project

Clone the repository:

```bash
git clone https://github.com/yourusername/mobile-price-prediction-ml.git
```

Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

Run the notebook:

```
Open task1.ipynb in Jupyter Notebook or Goog
```
