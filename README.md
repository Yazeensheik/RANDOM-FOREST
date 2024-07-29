# RANDOM-FOREST
RANDOM FOREST OF ADVANCE MACHINE LEARNING
# Random Forest Temperature Prediction

This repository contains code to build a Random Forest model to predict temperatures based on historical data.

## Dataset

The dataset used for this project is `temperature.csv`, which contains the following columns:
- `year`: The year of the observation
- `month`: The month of the observation
- `day`: The day of the observation
- `week`: The day of the week of the observation
- `temp_2`: The temperature two days prior
- `temp_1`: The temperature one day prior
- `average`: The historical average temperature for that day
- `actual`: The actual temperature on that day
- `friend`: The temperature reported by a friend

## Project Structure

- `RandomForest.ipynb`: The Jupyter Notebook containing the code for loading the data, preprocessing, and training the Random Forest model.
- `temperature.csv`: The dataset used for training and testing the model.

## Requirements

To run the code in this repository, you will need the following packages:

- pandas
- numpy
- scikit-learn
- matplotlib (optional, for visualization)

You can install these packages using pip:

```sh
pip install pandas numpy scikit-learn matplotlib
