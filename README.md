# 🌍 Greenhouse Gas Emission Predictor

This project presents a machine learning-powered web application that predicts **Supply Chain Emission Factors with Margins** using various **Data Quality (DQ) metrics**, based on a dataset of US industry and commodity emission factors. Built with **Streamlit**, this tool provides a quick and interactive way to estimate emissions for different substances.

## 🔍 Overview

Greenhouse gas (GHG) emissions from supply chains play a critical role in assessing the environmental footprint of industries. This application leverages a regression model to predict the **Supply Chain Emission Factors with Margins** using:
- Type of substance
- Source of data (commodity or industry)
- Unit of measurement
- DQ metrics such as reliability, temporal correlation, geographical coverage, technological representation, and data collection quality.

## 📁 Project Structure
├── app.py # Streamlit app

├── GHG.ipynb # Model training and data preprocessing notebook

├── SupplyChainEmissionFactorsforUSIndustriesCommodities.xlsx # Raw dataset

├── models/
│ ├── LR_model.pkl # Trained linear regression model

│ └── scaler.pkl # StandardScaler used for feature normalization

├── utils/

│ └── preprocessor.py # Data preprocessing functions

├── requirements.txt # Python dependencies

## 🚀 Features

- Interactive web UI built using **Streamlit**
- Supports input for various GHG substances
- Adjustable DQ metrics through sliders
- Displays prediction result instantly
- Lightweight and easy to run locally

## 📊 Dataset

The dataset used in this project is sourced from:
> **Supply Chain Emission Factors for US Industries and Commodities**

It includes values such as:
- Emission factors (with and without margins)
- Substance type
- Source type
- Associated data quality metrics

## 🧠 Model

A **Linear Regression** model was trained using `scikit-learn` to predict the emission factor with margins. The model was trained on scaled features, and both the model and scaler are stored in the `models/` directory.

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/GHG-Emission-Predictor.git
   cd GHG-Emission-Predictor
2.**Install dependencies**
   
    pip install -r requirements.txt

3. **Run the app**

      streamlit run app.py
   
## 🙌 Acknowledgements
Dataset Source: Supply Chain Emission Factors

Developed using: Python, Scikit-learn, Streamlit

Special thanks to AICTE, Edunet Foundation, and Shell for the guidance and opportunity.

## 💡 Future Work
Expand to multiple regression models and model selection

Add model evaluation metrics to the UI

Include visualizations of predicted vs actual values

Deploy on platforms like Streamlit Cloud or Render
## 📬 Contact
   Atharva Joshi
## Gmail: atharvajoshi046@gmail.com
## 🔗[GitHub Profile](https://github.com/atharvaajaj)
