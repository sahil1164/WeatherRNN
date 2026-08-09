# 🌦️ Weather Forecasting using RNN

A machine learning project that uses a **Recurrent Neural Network (RNN)** to predict the next day's maximum temperature from historical weather data.

The project was developed using **Python and Google Colab** with **TensorFlow/Keras**.

## 📌 Overview

The model learns temporal patterns from historical weather observations using a sliding-window approach.

For each prediction, the model uses the previous **10 days of maximum temperature** to predict the following day's maximum temperature.

## 🛠️ Technologies

- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Matplotlib
- Google Colab

## 🧠 Model

The project uses a stacked `SimpleRNN` architecture with:

- 50 RNN units
- Dropout regularization
- Dense output layer
- Adam optimizer
- Mean Squared Error (MSE) loss
- 10-day input sequence

## 🔄 Workflow

1. Load historical weather data
2. Preprocess the dataset
3. Create 10-day sliding-window sequences
4. Split the data into training, validation, and test sets
5. Train the RNN
6. Generate temperature predictions
7. Compare predicted and actual temperatures
8. Predict the next day's temperature

## 📊 Dataset

The project uses the **Seattle Weather Dataset** from Kaggle:

https://www.kaggle.com/datasets/mahdiehhajian/seattle-weather

The dataset is **not included in this repository**.

The notebook uses Google Colab's file-upload functionality to load the CSV dataset.

## 🚀 Running the Project

1. Open `WeatherForecastingUsingRNN.ipynb` in Google Colab.
2. Download the Seattle Weather Dataset from Kaggle.
3. Run the notebook.
4. Upload the downloaded CSV when prompted.
5. Execute the remaining cells to train the model and generate predictions.

## 📁 Project Structure

```text
WeatherRNN/
├── WeatherForecastingUsingRNN.ipynb
└── README.md
