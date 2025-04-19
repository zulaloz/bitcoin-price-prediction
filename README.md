# Bitcoin Price Prediction with Deep Learning Models

This project explores the prediction of Bitcoin prices using a variety of deep learning models. It includes comparisons between baseline methods and advanced neural networks, including:

- Naive Forecasting
- Dense Neural Networks (various window/horizon configurations)
- Conv1D
- LSTM
- N-BEATS Algorithm
- Model Ensembling
- Future Value Prediction

## 📊 Dataset
The dataset contains daily closing prices of Bitcoin from 2013 to 2021, sourced from CoinDesk.

## 🔧 Techniques
- Time series preprocessing and windowing
- Model evaluation using MAE, RMSE, MAPE, and MASE
- Visualization of training/test splits and predictions
- TensorFlow model saving/loading and checkpointing

## 📁 Structure
- `bitcoin_price_prediction.ipynb`: Jupyter Notebook of the full pipeline
- `bitcoin_price_prediction.py`: Python script version
- `report/`: Includes academic paper and slide presentation
- `images/`: Folder for model output plots
- `README.md`: This file
- `requirements.txt`: Dependencies for running the code

## ⚙️ Installation

```bash
pip install -r requirements.txt
```

## 👩‍💻 Author
Zülal Özyazıcıoğlu