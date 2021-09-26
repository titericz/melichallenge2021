# melichallenge2021
MELI DATA CHALLENGE 2021 - https://ml-challenge.mercadolibre.com/

Run each notebook in the order:

- 1-preprocess.ipynb 
# converts trainset all to numerical data.

- 2-valid-and-train-day-1-boost.ipynb 
# train model forecasting probability of runout of stock in day+1

- 3-valid-and-train-day-2-boost.ipynb
# train model forecasting probability of runout of stock in day+1 + day+2

- 4-valid-train-target-mean30days.ipynb
# train model forecasting probability of runout of stock in day+1 .. day+30

- 5-ensemble.ipynb
# ensemble models trained in 2, 3 and 4.
