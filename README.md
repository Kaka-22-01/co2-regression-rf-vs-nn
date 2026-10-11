# CO2 Prediction Random Forest vs Neural Network

Predict CO2 values from 3 input features and compare a Random Forest with a neural network.

## Dataset 
- Source: (`co2.csv`)
- Features: (`engine` , `cylandr` , `fuelcomb`)
- Target: (`out1`)

## Results

|Model|R2|MAE|
|-----|--|---|
|Random Forest|95.23|7.34|
|Neural Network|90.10|13.56|
5-fold cross-validation for Random Forest : mean R² = 0.92.

Random Forest performed better on this small tabular dataset.

## Files
- `code.ipynb` : the full notebook with code and outputs.
- `co2.csv` : the dataset.

## Tools 
Python , pandas , scikit-learn , Tensorflow/Keras

## How to Run
1. Clone the repository.
2. Install the libraries: `pip install pandas scikit-learn tensorflow`
3. Open `code.ipynb` and click Run All.