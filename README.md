# 📊 Bank Customer Churn Prediction

## Overview
This project predicts customer churn in the banking sector using an **Artificial Neural Network (ANN)**. The model is deployed via **Streamlit**, providing an interactive interface for **real-time predictions and insights** to help financial institutions **proactively retain at-risk customers**.

## 🚀 Features
- **Customer Churn Prediction**: Uses an ANN model trained on historical banking data to identify potential churn.
- **Real-Time Risk Assessment**: Enables banks to **engage customers before they leave**, optimizing retention efforts.
- **Interactive Web Application**: Streamlit-powered UI for intuitive user interaction.
- **Preprocessing Pipeline**: Automated feature engineering, encoding, and scaling for accurate predictions.

## 🛠️ Installation

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/SuryaVegesna27/Bank-Customer-Churn-Prediction.git
cd Bank-Customer-Churn-Prediction
2️⃣ Install Dependencies
Ensure you have Python installed, then run:

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the Streamlit App
bash
Copy
Edit
streamlit run app.py
Open the provided local URL in your browser to start using the model.

📂 Repository Contents
Churn_Modelling.csv → Banking dataset used for training.
experiments.ipynb → Exploratory data analysis and model training.
app.py → Streamlit application script.
model.h5 → Trained ANN model.
scaler.pkl, label_encoder_gender.pkl, ohe_geography.pkl → Preprocessing objects.
requirements.txt → Python dependencies.
🔍 Results
85% Accuracy in predicting churn.
Helps banks prioritize high-risk customers for personalized retention strategies.
🤝 Contributing
Want to improve the model or UI? Fork the repo and submit a pull request!

📜 License
This project is licensed under the MIT License.
