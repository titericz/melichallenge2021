# melichallenge2021
MELI DATA CHALLENGE 2021 - https://ml-challenge.mercadolibre.com/

Run each notebook in the order:

- Converts trainset all to numerical data.
1-preprocess.ipynb 

# Train model forecasting probability of runout of stock in day+1
2-valid-and-train-day-1-boost.ipynb 


# Train model forecasting probability of runout of stock in day+1 + day+2
3-valid-and-train-day-2-boost.ipynb


# Train model forecasting probability of runout of stock in day+1 .. day+30
4-valid-train-target-mean30days.ipynb


# Ensemble models trained in 2, 3 and 4.
5-ensemble.ipynb
