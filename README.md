#  WeatherWise — Weather Forecasting and ML

WeatherWise is a Python-based weather forecasting application that displays a seven-day forecast for a city and demonstrates machine learning-based rain prediction through an interactive dashboard.

##  Features

- Search weather forecasts by city.
- Display seven-day temperature and rain probability.
- Show weather conditions with icons.
- Interactive dashboard built with Gradio.
- Random Forest machine learning model for rain prediction.
- Model evaluation using accuracy, classification report, and confusion matrix.

##  Technologies Used

- Python
- Google Colab
- Gradio
- Pandas
- Scikit-learn
- Matplotlib
- Open-Meteo API

##  Machine Learning

The Random Forest classifier is trained on historical Australian weather data using six features: minimum temperature, maximum temperature, rainfall, humidity at 3 PM, pressure at 3 PM, and wind speed at 3 PM.

The model achieved approximately **83.96% test accuracy** in the current experiment. Its recall for rainy days was approximately 45%.

**Limitation:** The model uses Australian historical weather data and the current dashboard integration includes assumed values for some inputs. Therefore, its prediction is a demonstration and is not calibrated for reliable local weather forecasting.

##  Dataset

Historical weather dataset: [Weather Australia Dataset](https://rattle.togaware.com/weatherAUS.csv)

Weather forecast API: [Open-Meteo](https://open-meteo.com/)

##  How to Run

1. Open `Weather_prediction.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. Wait for the ML model to train.
4. Launch the Gradio application.
5. Enter a city name to view the forecast and ML demonstration.

##  Note

The Gradio share link generated through Google Colab is temporary. If the runtime resets, rerun the notebook cells to launch the application again.
