# 02_COVID-19-PREDICTION
COVID-19 Global Cases & Deaths Prediction Time-Series Forecasting using Polynomial Regression

📌 Overview This project uses global time-series data of COVID-19 confirmed cases and deaths to forecast future trends using Polynomial Regression. It processes historical data, visualizes real trends, trains regression models, and forecasts the next 30 days of the pandemic trajectory.

The project is implemented in Google Colab using Python libraries such as Pandas, Matplotlib, and Scikit-learn.

📁 Dataset Description Three CSV files were used:

CONVENIENT_global_confirmed_cases.csv: Time-series data for global confirmed cases

CONVENIENT_us_confirmed_cases.csv: (Optional – not used in this project)

CONVENIENT_global_deaths.csv: Time-series data for global confirmed deaths

Each file contains:

Row 0: Metadata (Province/State, Country/Region, etc.)

Row 1 onward: Daily records from January 2020 with values for each country

Columns: Date-wise columns or country-wise rows, depending on the structure

⚙️ Project Structure The code is written in blocks suitable for Colab. It includes:

✅ Case Analysis: Load and preprocess the global cases file

Aggregate global totals per date

Train Polynomial Regression (degree = 3)

Visualize actual vs predicted cases

Forecast next 30 days and plot predictions

✅ Death Analysis: Load and preprocess the global deaths file

Aggregate global totals per date

Train Polynomial Regression (degree = 3)

Visualize actual vs predicted deaths

Forecast next 30 days and plot predictions

📊 Key Techniques Used Polynomial Regression (degree=3)

Feature Engineering: Days since start date as numerical feature

Time-Series Forecasting

Matplotlib for trend and prediction visualization

📈 Output Line plots of historical cases and deaths

Polynomial fit curves for training data

Forecast plots for the next 30 days (both cases and deaths)

🛠️ How to Run (Google Colab) Upload required CSV files.

Run the notebook block-by-block.

Adjust parameters (e.g., degree of polynomial, forecast days) as needed.

🔍 Example Graphs Global Cases Over Time

Polynomial Regression Fit (Cases)

Forecasted Global Cases

Global Deaths Over Time

Polynomial Regression Fit (Deaths)

Forecasted Global Deaths

📌 Requirements Python 3.x

pandas

numpy

matplotlib

scikit-learn

(Pre-installed on Colab)

📅 Future Work Try other regression models (e.g., SVR, Random Forest)

Add country-specific predictions

Use real-time API data (e.g., Johns Hopkins GitHub)

Evaluate model accuracy (RMSE, MAE)



👤 Author Created by Amit Project for time-series forecasting of COVID-19 using machine learning
