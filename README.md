# Energy Consumption Forecasting using RNN & LSTM

This repository presents a comprehensive time-series forecasting project using SimpleRNN and LSTM architectures. It is based on the **Appliances Energy Prediction** dataset and was developed as part of the ADTA 5560 Neural Network course.

##  Dataset

- **Source:** UCI Machine Learning Repository  
- **Access:** [Kaggle Link](https://www.kaggle.com/datasets/sohommajumder21/appliances-energy-prediction-data-set)  
- **Size:** 19,735 rows × 29 columns  
- **Task:** Predict future appliance energy usage based on environmental variables.

##  Project Highlights

### PART II: Simple RNN on Sine Wave
- Modeled a synthetic sine wave to demonstrate basic sequential prediction.
- Achieved low MSE with a basic SimpleRNN structure.

### PART III–V: LSTM on Real Dataset
- Built and trained a 3-layer LSTM model to predict energy consumption.
- Used Dropout for regularization and Adam optimizer with MSE loss.
- Retrained model on full data and forecasted 107 future points.

### PART VI: Model Redesign
- Enhanced model with 4 LSTM layers, longer input sequence (100 timesteps), and advanced regularization (Dropout 0.3).
- Improved accuracy and robustness in forecasting.

### PART VII: Final Comparison & Insights
- Compared original and redesigned networks.
- Found that the deeper LSTM significantly outperforms SimpleRNN and basic LSTM in accuracy and generalization.

##  Tech Stack

- Python 3.9+
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib
- Jupyter Notebook



##  Key Learning

- RNNs are simple but limited in handling long-term dependencies.
- LSTMs overcome gradient issues and perform well on real-world forecasting.
- Model tuning (layers, dropout, epochs, optimizer) significantly affects performance.

