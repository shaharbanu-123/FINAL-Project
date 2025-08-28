# FINAL-Project
# PM₁₀ Forecasting (LSTM, GRU, CNN)

This project analyzes **daily PM₁₀ air quality data (West Bengal, 2010)** and applies deep learning models (**LSTM, GRU, CNN**) to forecast air pollution levels. The code is implemented in **Python (Google Colab)** with TensorFlow/Keras.

---

##  Features
- Data preprocessing and visualization (histograms, line plots, heatmaps, violin plots).  
- Time-series scaling and supervised learning sequence creation.  
- Model implementations:  
  - **LSTM** – single-layer recurrent neural network.  
  - **GRU** – stacked gated recurrent units with dropout.  
  - **CNN** – 1D convolutional network for time-series forecasting.  
- Model evaluation with metrics:  
  - MAE, MSE, RMSE, MAPE, R²  
  - Forecasting Accuracy (%)  
- Residual plots for error analysis.  

---

##  Requirements
Install dependencies before running:
```bash
pip install tensorflow scikit-learn matplotlib seaborn numpy pandas
