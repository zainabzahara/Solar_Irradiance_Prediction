# Solar Irradiance Prediction

This repository contains code for predicting solar irradiance using two different models: a transformer-based model and a genetic algorithm (GA) model. The goal is to accurately forecast solar irradiance, which can help optimize the operation and energy output of photovoltaic (PV) systems.


## Files

- `transformer.ipynb`: Implementation of the transformer-based model for solar irradiance prediction.
- `GA.ipynb`: Implementation of the genetic algorithm (GA) model for solar irradiance prediction.

## Dataset

The dataset used for this project is stored on Google Drive and is loaded within the notebooks.

## Methodologies

### Transformer Model

The transformer model is implemented using PyTorch and involves the following steps:
1. Data Preprocessing: Cleaning, normalizing, and transforming the data into sequences.
2. Model Definition: Defining a transformer-based model.
3. Training: Training the model and evaluating it using training and validation datasets.
4. Evaluation: Making predictions and calculating performance metrics such as MSE, RMSE, MAE, and R².

### Genetic Algorithm (GA) Model

The GA model involves the following steps:
1. Data Preparation: Loading, cleaning, normalizing, and converting the data into supervised learning format.
2. Model Definition: Defining an LSTM model and optimizing it using a genetic algorithm to find the best hyperparameters.
3. Training: Training the final model using the optimal hyperparameters.
4. Evaluation: Making predictions and calculating performance metrics.

## Results

The performance of both models is evaluated using the following metrics:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score (R²)

The results are plotted to visually compare the actual and predicted values for the training, validation, and test datasets.

The results indicate that the transformer model generally performed better than the GA model, especially in terms of the R² metric during testing.


## Conclusion

Both the transformer-based model and the GA-optimized LSTM model show promising results for short-term solar irradiance prediction. Future work could involve integrating additional features, exploring different model architectures, and incorporating real-time data for continuous model improvement.

## How to Run

1. Clone this repository.
2. Ensure you have the necessary dependencies installed.


## License

[MIT](https://choosealicense.com/licenses/mit/)


