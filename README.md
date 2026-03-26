# Flight Price Prediction

- The project develops a Machine Learning model to predict flight ticket prices based on factors such as airline, route, departure date, duration, and number of stops.
- It helps understand pricing patterns and enables data-driven decision-making for travellers.

## Problem Statement

Flight ticket prices fluctuate due to multiple factors, including demand, booking time, route, and seasonality.
The objective of this project is to:
- Predict flight prices accurately
- Identify key factors influencing price variations

## Key Metrics

- Model: Random Forest Regressor
- MAE: ~316
- RMSE: ~667

## Tech Stack

- Language: Python
- Libraries: pandas, numpy, scikit-learn

## Project Structure

- 'data/' -> Dataset used for training
- 'notebooks/' -> Main ML notebook

## Architecture

- Data Collection -> Data Cleaning & Preprocessing -> Feature Engineering -> Model Training (Random Forest) -> Model Evaluation

## Key Insights

- Ticket prices increase significantly closer to the departure date
- Flights with more stops are generally cheaper
- Peak seasons (holidays, summer) show higher price trends
- Route and distance play a major role in pricing

## How to Run

1. Clone the repository
2. Install dependencies
```
pip install -r requirements.txt
```
3. Open Jupyter Notebook
```
```

## Future Improvements

- Try advanced models like XGBoost
- Deploy using Flask/Streamlit

## Author

Akshat Jain

Aspiring Data Analyst| Machine Learning Enthusiast| 
Skilled in Python, SQL, and Data Analysis

LinkedIn: https://www.linkedin.com/in/akshat-jain-934098250
