# Pipeline Breakage Prediction – Samsung Innovation Campus 2025

## 📌 Overview

This project was developed as part of the **Samsung Innovation Campus 2025** programme and focuses on the prediction of pipeline failures in the Peruvian jungle.

The project combines environmental and structural sensor data with machine learning and time-series forecasting techniques to investigate the factors associated with pipeline breakages and develop predictive models.

The overall approach included **data preprocessing, clustering, rainfall forecasting using recurrent neural networks (RNNs), and supervised machine learning models for pipeline breakage prediction**.

---

## 🎯 Problem Statement

Pipeline infrastructure in the Peruvian jungle is exposed to challenging environmental conditions, including heavy rainfall and changes in soil and groundwater conditions.

Pipeline failures can result in significant environmental, economic and operational consequences. Early identification of conditions associated with potential failures could help support preventive maintenance and improve the management of pipeline infrastructure.

The objective of this project was therefore to explore historical environmental and structural measurements and develop a data-driven approach for predicting conditions associated with pipeline breakages.

---

## 💡 Proposed Solution

The proposed solution follows a multi-stage machine learning pipeline:

1. **Data preprocessing and exploration**
2. **Clustering of environmental and structural conditions**
3. **Rainfall forecasting**
4. **Pipeline breakage prediction**
5. **Comparison and evaluation of different machine learning models**

The rainfall forecasting component was designed to provide future precipitation information that could subsequently be incorporated into the analysis of pipeline failure risk.

---

## 📊 Dataset & Data Sources

The project uses historical environmental and structural measurements collected from pipeline infrastructure in the Peruvian jungle.

The data includes measurements from different types of sensors, including:

* 🌧️ **Rain gauges (pluviometers)** – rainfall measurements
* 📏 **Strain gauges** – measurements related to structural deformation
* 💧 **Piezometers** – measurements related to groundwater pressure and soil conditions

The historical data covers the period **2004–2018**.

Before modelling, the data was processed and prepared to address issues such as missing values, temporal information and differences between sensor measurements.

> **Note:** Raw datasets and project-specific data files are included in the repository where permitted by the project and dataset conditions.

---

## 🧠 Methodology

### 1. Data Preprocessing

The first stage consisted of preparing the historical sensor data for analysis and machine learning.

The preprocessing pipeline included:

* Data cleaning
* Handling missing values
* Data transformation
* Feature preparation
* Temporal organisation of observations
* Exploratory data analysis

The objective was to obtain consistent datasets suitable for both time-series forecasting and supervised machine learning.

---

### 2. Clustering

Unsupervised learning techniques were used to identify groups of observations with similar environmental and structural characteristics.

Clustering allowed the project to investigate whether different combinations of environmental conditions could be associated with different pipeline behaviours or failure patterns.

This stage provided an additional way of understanding the structure of the dataset before applying supervised prediction models.

---

### 3. Rainfall Prediction

Because rainfall can play an important role in the environmental conditions surrounding pipeline infrastructure, a dedicated forecasting component was developed.

A **Recurrent Neural Network (RNN)** approach was used to model the temporal behaviour of rainfall and generate future precipitation predictions.

The forecasting stage was designed to provide predictions for a future horizon of up to **100 days**, which could then be considered as an input to the wider pipeline-risk analysis.

---

### 4. Pipeline Breakage Prediction

The final stage focused on predicting pipeline breakage events using supervised machine learning.

Several classification algorithms were investigated:

* **Support Vector Machine (SVM)**
* **Random Forest**
* **XGBoost**

The models were trained and evaluated using the processed environmental and structural data in order to investigate their ability to distinguish between conditions associated with pipeline failure and non-failure events.

---

## 🤖 Machine Learning Models

| Model         | Type                        | Purpose                      |
| ------------- | --------------------------- | ---------------------------- |
| RNN           | Deep Learning / Time Series | Rainfall forecasting         |
| SVM           | Supervised Learning         | Pipeline breakage prediction |
| Random Forest | Ensemble Learning           | Pipeline breakage prediction |
| XGBoost       | Gradient Boosting           | Pipeline breakage prediction |

The use of several different algorithms allowed the project to compare different modelling approaches rather than relying on a single predictive method.

---

## 📈 Results

The project demonstrated the feasibility of combining environmental forecasting with machine learning to investigate pipeline breakage risk.

The modelling process provided:

* A structured preprocessing pipeline for heterogeneous sensor data
* Identification of patterns within environmental and structural measurements
* Rainfall forecasting using recurrent neural networks
* Comparison of multiple supervised machine learning algorithms
* A framework for investigating potential pipeline failure conditions

Detailed model outputs, visualisations and analysis can be found in the `notebooks/` and `reports/` directories.

---

## 🛠️ Technologies & Tools

### Programming & Data Science

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**

### Machine Learning

* Support Vector Machines (SVM)
* Random Forest
* XGBoost
* Recurrent Neural Networks (RNN)

### Data Analysis & Visualisation

* Jupyter Notebook
* Matplotlib
* Seaborn

### Development

* Git
* GitHub

---

## 👩‍💻 My Contribution

This was a **collaborative project developed as part of the Samsung Innovation Campus 2025 programme**.

My contribution included working on the project's data science and machine learning workflow, including data preparation, exploratory analysis, modelling and evaluation.

I also contributed to the development and analysis of the predictive approach for environmental conditions and pipeline breakage.

> **Note:** This repository is a fork of the team's original repository. The project was developed collaboratively, and individual contributions should be considered within the context of the complete team project.

---

## 👥 Team

**Samsung Innovation Campus 2025 – Project Team**

* **Carolina Carter de Ortueta**
* **Fátima Ximena Miranda Deza**
* **Marjorie Coria**

---

## 🏆 Samsung Innovation Campus 2025

This project was developed during the **Samsung Innovation Campus 2025** programme, an educational programme focused on developing practical skills in artificial intelligence, data science and emerging technologies.

The project was selected as a **finalist** during the programme.

---

## 📁 Project Structure

```text
Samsung-Innovation-Campus-Pipeline-Prediction/
│
├── data/
│   └── Dataset and processed data
│
├── notebooks/
│   └── Jupyter notebooks for analysis and modelling
│
├── reports/
│   └── Project reports and generated analysis
│
├── src/
│   └── Source code and modelling components
│
├── main.py
│   └── Main project entry point
│
├── requirements.txt
│   └── Python dependencies
│
└── README.md
    └── Project documentation
```

---

## 🚀 Future Improvements

Potential future improvements include:

* Incorporating additional environmental and geological variables
* Improving the rainfall forecasting architecture
* Testing more advanced time-series models
* Optimising model hyperparameters
* Addressing class imbalance in pipeline failure events
* Improving model interpretability
* Developing a real-time monitoring and early-warning system
* Deploying the predictive model as an operational decision-support tool

---

## 📄 License

This repository contains work developed as part of the **Samsung Innovation Campus 2025** programme.

Please refer to the original project and dataset documentation for information regarding the use and redistribution of the included materials.
