# Bike-Sharing-Demand-Prediction

# Bike Sharing Demand Prediction

## Project Overview and Purpose
[cite_start]This project focuses on predicting the demand for shared bicycles in a city based on environmental and seasonal factors[cite: 1]. [cite_start]Using datasets that track rentals on both a daily and hourly basis, the project aims to identify key drivers of bike usage and build a predictive model to forecast future demand[cite: 1, 3].

## Key Technologies and Libraries
- **Python**: Core programming language.
- **Data Analysis**: `pandas`, `numpy`.
- **Data Visualization**: `matplotlib`, `seaborn`.
- **Machine Learning**: `scikit-learn`.
- [cite_start]**Deep Learning**: `tensorflow` / `keras`[cite: 1].

## Data and Methodology
### Dataset
The analysis uses two primary files:
- [cite_start]`day.csv`: Daily rental counts (731 records)[cite: 1].
- [cite_start]`hour.csv`: Hourly rental counts (17,379 records)[cite: 1].
- [cite_start]**Key Features**: Season, weather situation, temperature (normalized), humidity, and windspeed[cite: 1, 2].

### Workflow
1. [cite_start]**Exploratory Data Analysis (EDA)**: Analyzed correlations between weather conditions and rental volume[cite: 1].
2. [cite_start]**Preprocessing**: Handled normalization of environmental variables like temperature and humidity[cite: 1, 2].
3. [cite_start]**Modeling**: Built a Deep Learning model (Multi-Layer Perceptron) using Keras[cite: 1].
4. [cite_start]**Evaluation**: Optimized the model over 50 epochs, achieving a Test Mean Squared Error (MSE) of approximately 1001.59[cite: 1].

## Results and Insights
- [cite_start]**Performance**: The final model reached an R² score that indicates strong predictive capability for bike counts[cite: 1].
- [cite_start]**Key Finding**: Temperature and time of day (hour) are the most significant predictors of bike rental frequency[cite: 1, 2].

## How to Run Locally
1. **Clone the repo**: `git clone <your-repo-url>`
2. **Install requirements**: `pip install -r requirements.txt`
3. **Launch Notebook**: Open `notebooks/Bikes_Sharing.ipynb` in Jupyter or Google Colab.
