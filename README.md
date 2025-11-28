# stock_price_predictor_LSTM
Mini Project as the part of College Assignment : Stock Price Predictor using LSTM

📈Stock Price Predictor (LSTM Deep Learning Model) : 

A machine learning project that predicts future stock prices using historical data, technical indicators, and an LSTM (Long Short-Term Memory) network — with your analysis and model implemented in a Colab notebook.



📝 Project Overview

This project builds a time-series forecasting model to predict future stock closing prices based on past data. It includes:

Fetching historical stock data (via API)

Computing technical indicators (e.g., moving averages, RSI)

Training LSTM-based deep learning models

Visualizing actual vs. predicted prices

Generating basic “Buy / Sell / Hold” suggestions based on model output

All code, analysis and visualizations are implemented in a Colab notebook for easy execution and reproducibility.



💻 Interactive Notebook (Run in Colab)

You can run and experiment with the project directly in Colab using the following link:

Open in Colab → Stock Price Predictor Notebook

This notebook contains: data collection, preprocessing, model training, evaluation and visualization.




🔧 Tech Stack & Libraries

The project uses:

pandas, numpy — data handling & numerical operations

matplotlib, seaborn — static data visualization

plotly — interactive charts

yfinance (or similar API) — fetching stock data

scikit-learn — preprocessing (scaling, train/test splitting)

tensorflow / keras — building and training the LSTM model



How to Use / Run

Click the Colab link above → open the notebook

Optionally change runtime: Runtime → Change runtime type → GPU

Run all cells (or step-by-step) — the notebook will:

Download historical stock data

Preprocess and scale data

Build & train LSTM model

Plot actual vs predicted prices

Show evaluation metrics (RMSE, MAE)

Optionally provide a simple “Buy / Sell / Hold” suggestion based on predictions

(Optional) If you want to save/export model and code, you can copy the notebook content into modular Python scripts, or download the notebook as .ipynb / .py.




⚙️ How to Run Locally (Windows)

1. Create & activate virtual environment. 

python -m venv venv

venv\Scripts\activate

2. Install dependencies

pip install -r requirements.txt

3. Run the notebook

jupyter notebook

Open your .ipynb file and run all cells.
OR run Python script
python main.py
