
# 🔥 Forest Fire Prediction - Algerian Dataset

This project uses machine learning to predict the likelihood or extent of forest fires based on environmental and meteorological conditions. It is built with a clean ML workflow including EDA, preprocessing, model training, and basic UI development using Flask (local).

## 📁 Project Structure

```
fire-forest-prediction/
│
├── app.py                       # Flask app to serve the model locally
├── templates/
│   └── index.html               # Web UI for input and results
│
├── eda_notebook.ipynb           # Exploratory Data Analysis
├── model_training.ipynb         # Model building and evaluation
├── forest_model.pkl             # Trained ML model
├── scaler.pkl                   # Preprocessing scaler
│
├── requirements.txt             # Project dependencies
└── README.md                    # Project overview
```

## 📊 Dataset

- **Source**: Algerian Forest Fire Dataset
- **Features**: Temperature, Relative Humidity, Wind, Rain, and Fire Weather Index variables.
- **Target**: Fire occurrence or severity.

