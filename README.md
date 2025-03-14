# 🌍 Weather Trend Forecasting

A project for forecasting global weather trends using **ARIMA, Prophet, and advanced data science techniques**.

## 📌 Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## 📖 Introduction
This project leverages **time-series forecasting** models like **ARIMA and Facebook Prophet** to analyze and predict weather patterns. The dataset consists of global weather data, including temperature, humidity, and air quality metrics.

## 📊 Dataset
The dataset contains weather information such as:
- **Temperature (°C & °F)**
- **Humidity (%)**
- **Air Quality (PM2.5, PM10)**
- **Wind Speed (mph)**
- **Sunrise & Sunset Times**
- **Moon Phase & Illumination**

Stored in **`GlobalWeatherRepository.csv`**, it spans from **May 16, 2024, to March 14, 2025**.

## 🔬 Methodology
We implement two forecasting models:
1. **ARIMA (AutoRegressive Integrated Moving Average)** for time-series trend analysis.
2. **Facebook Prophet** for robust trend prediction with seasonality consideration.
3. **Ensemble Learning** combining both models for improved accuracy.

Evaluation Metrics:
- **Mean Absolute Error (MAE)**
- **Root Mean Square Error (RMSE)**

## ⚙️ Installation
Clone this repository and install the required dependencies:

    
    git clone https://github.com/RSaivarsha/Weather_Trend_Forecasting.git
    cd Weather_Trend_Forecasting
    pip install -r requirements.txt

## 🚀 Usage

Run the Jupyter Notebook:
    
    
    jupyter notebook

## 📊 Results

The performance of different models:

- ARIMA Forecast 📉
- Prophet Forecast 📈
- Ensemble Model ⚡

See the *results/* folder for detailed visualizations.

---

## 💛 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit changes (`git commit -m "Added new feature"`)
4. Push to the branch (`git push origin feature-name`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 🎉 Happy Forecasting! ☁️
