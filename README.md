
# Time Series Forecasting using Convolutional Temporal Transformer Model

This project implements a Convolutional Temporal Transformer (CTT) model for time series forecasting. The model is designed to handle diverse datasets and extract meaningful patterns from temporal data.

## Datasets

### 1. **Private Veggies Dataset**
   - Contains historical price data for vegetables along with external factors such as weather, fuel prices, and exchange rates.

### 2. **Electric Power Consumption Dataset**  
   - [Kaggle Link](https://www.kaggle.com/datasets/fedesoriano/electric-power-consumption)  
   - This dataset includes measurements of electric power consumption over time, featuring attributes like global active power, voltage, and energy sub-metering.

### 3. **Sunspot Data from SILSO**  
   - [SILSO Link](https://www.sidc.be/SILSO/datafiles)  
   - Provides data on daily and monthly sunspot numbers, which are used for forecasting solar activity patterns.

## Model Overview

The Convolutional Temporal Transformer (CTT) model combines:
- **Convolutional Neural Networks (CNN)** for feature extraction.
- **Transformer Encoders** for capturing temporal dependencies and global context.

### Key Features
- Multi-dataset compatibility for time series forecasting.
- Integration of convolutional layers for localized feature extraction.
- Temporal attention mechanisms for improved prediction accuracy.

## How to Use

### Prerequisites
- Python 3.x


## Results
The model is evaluated using standard metrics such as:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Coefficient of Determination (R²)

## Future Work
- Extend the model for real-time forecasting applications.
- Explore additional datasets for further validation.
- Optimize the model for deployment on edge devices.

## License
This project is licensed under the MIT License. 

