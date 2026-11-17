# Currency_Model_LSTM

Time-series forecasting with an **LSTM neural network** built in Keras. Several market data sources are merged into one dataset, the model is trained on it and then evaluated on validation and test data.

## What's inside

| File | Purpose |
|---|---|
| `DataExtractor.ipynb` | Merges the individual CSV data sources into one table (`integrated_data.csv`) |
| `Currency_Model_LSTM.ipynb` | Builds and trains the LSTM model |
| `testowanie.ipynb` | Model evaluation |
| `testowanie_zbior_testowy.ipynb` | Evaluation on the hold-out test set |
| `model.json`, `model.h5` | Saved model architecture and weights |
| `correlations.csv` | Correlations between the explanatory variables |

## Stack

Python · pandas · Keras / TensorFlow · Jupyter

## How to run

1. Open `DataExtractor.ipynb` to rebuild `integrated_data.csv` (or use the file already in the repo).
2. Run `Currency_Model_LSTM.ipynb` to train the model, or load the saved `model.json` + `model.h5`.
3. Use the `testowanie*` notebooks to evaluate the predictions.
