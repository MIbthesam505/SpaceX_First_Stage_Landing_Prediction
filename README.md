# 🚀 SpaceX Falcon 9 First Stage Landing Prediction

This project is part of a data science capstone, where we aim to predict whether the **Falcon 9 first stage** will land successfully.

Since SpaceX can reuse the first stage of its Falcon 9 rockets, their launch costs are significantly lower ( $62 Million per lauch instead of others who do $165 Million + . Predicting the landing outcome is not only important for understanding mission success but also for evaluating the economic advantages of reusability.

## 📌 Project Overview

* Collect and preprocess data from the **SpaceX API** and public datasets
* Perform **Exploratory Data Analysis (EDA)** using Matplotlib and Seaborn
* Visualize geospatial data with **Folium** for interactive mapping of launch sites
* Build and evaluate **Machine Learning models** to predict landing success
* Analyze the key factors affecting outcomes, such as payload mass, orbit type, and launch site location

## 🔑 Key Features

* Interactive **launch site maps** with markers and proximity analysis
* Insights into how launch conditions affect success rates
* Comparison of SpaceX launch economics with other providers
* End-to-end data science workflow: data collection → EDA → visualization → ML models

## 🛠️ Technologies Used

* **Python**
* **Pandas / NumPy** – data wrangling
* **Matplotlib / Seaborn** – visualization
* **Folium** – interactive maps
* **Scikit-learn** – machine learning models


## 📂 Project Structure

```
├── notebooks/           # Jupyter notebooks for EDA, visualization, ML
├── data/                # Raw and processed datasets
├── images/              # Plots, charts, and visualizations
├── README.md            # Project documentation
└── requirements.txt     # Python dependencies
```


## 🚀 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/MIbthesam505/SpaceX_First_Stage_Landing_Prediction
   ```
2. Install dependencies:

   ```bash
   pip install (mostly done directly in the jupyter notebooks)
   if necessary just go to cmd and write pip install nameofthelibrary
   ```
3. Open the notebooks:

   ```bash
   jupyter notebook
   ```


## 📊 Results

* Achieved predictive accuracy of **XX%** (update once you have results).
* Identified **payload mass** and **orbit type** as strong predictors of success.
* Built interactive maps showing how **launch site location** influences outcomes.


## ✨ Future Work

* Integrate real-time data from the SpaceX API
* Experiment with deep learning models
* Create a dashboard for visualization and prediction


## 🙌 Acknowledgements

This project is based on the **IBM Data Science Capstone** from Coursera, with data sourced from **SpaceX** and public repositories.

