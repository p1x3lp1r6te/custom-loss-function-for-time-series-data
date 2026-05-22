# Custom Loss Function for Time Series Forecasting

## Overview
This project introduces a custom loss function that combines Mean Squared Error (MSE) with a smoothness penalty to improve time-series predictions.

## Motivation
Standard loss functions like MSE do not enforce smooth predictions, which is critical in time-series tasks like stock prices and weather forecasting.

## Method
Custom Loss = λ₁(MSE) + λ₂(Smoothness Penalty)

- MSE ensures prediction accuracy
- Smoothness penalty reduces abrupt changes

## Datasets
- Jena Climate Dataset
- S&P 500 Dataset
- Google Finance Dataset

## Results
- Achieved R² score up to **0.9967**
- Outperformed MSE, MAE, and Huber Loss

## Tech Stack
- Python
- NumPy
- Machine Learning

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/custom-loss-time-series.git
cd custom-loss-time-series
```

### 2. Install Dependencies
Create a `requirements.txt` file from the libraries used in the notebooks and run:

```bash
pip install -r requirements.txt
```

### 3. Open the Jupyter Notebook
```bash
jupyter notebook
```

or

```bash
jupyter lab
```

### 4. Run the Notebook
Open any of the provided model notebooks and run the cells sequentially.

## Notes
- Datasets were not uploaded due to large file size.
- Update dataset paths inside the notebooks before running.
- The repository currently contains multiple model implementations in `.ipynb` format.
