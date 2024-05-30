# Bitcoin_Prediction
## Overview
This project aims to predict the next-day Bitcoin price using deep learning techniques, specifically LSTM (Long Short-Term Memory) models. The project involves data preparation, model training, and evaluation to forecast Bitcoin prices accurately.

## Project Structure
- **File:** Bitcoin_Price_Prediction.ipynb
- **Contents:**
  - Data preparation using YFinance for Bitcoin market data.
  - LSTM model training with 4 layers for price prediction.
  - Visualization of actual vs. predicted Bitcoin prices.
  - Evaluation of model directional accuracy.

## Key Steps
1. **Data Preparation:**
   - Extracted historical Bitcoin market data.
   - Preprocessed data by scaling and creating look-back windows.

2. **LSTM Model Training:**
   - Configured LSTM model with 4 layers and Adam optimizer.
   - Fitted the model with 100 epochs and full batch size.
   - Evaluated model performance using mean squared error.

3. **Model Evaluation:**
   - Calculated directional accuracy of the model.
   - Visualized actual vs. predicted Bitcoin prices.

## Results
- LSTM model achieved directional accuracy up to 58.25%.
- Optimal model configuration: 4 layers, 100 epochs, 600-day lookback.
- Model shows potential for trend analysis and price prediction in the cryptocurrency market.

## Conclusion
- LSTM model demonstrates promise in predicting Bitcoin prices.
- Continuous optimization of model parameters can enhance predictive capabilities.
- Further refinement and fine-tuning can improve forecasting accuracy for future price movements.
