# ML-Car-Dealership-predictions

Google Colab Notebook [![Open In Colab][colab-badge]][colab-notebook]

[colab-notebook]: <https://colab.research.google.com/github/tycoon-dev/ML-Car-Dealership-predictions/blob/main/Projeto_IA.ipynb>
[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>

A python implementation predicting car prices / age / fuel type. Data scrapped from StandVirtual and used for training the model.


A dataset was created by scrapping the website Standvirtual, a platform dedicated to sell both used and new cars in Portugal. Using HTML requests
and Regex, Important features were extracted (e.g: Car price, Car brand, Fuel Type, Engine power, etc)

Car price and Age prediction implements both Linear Regression using SKlearn and Catboost Regressor
Fuel type prediction implements Classification models like Kmeans and Catboost Classificator

# INSTRUCTIONS ON HOW TO RUN

OPTIONAL(Put linksDeCarros.txt inside the same folder if you want to train on a smaller set of entries)

1. COPY carrosFinal.csv to be in same folder as notebook
2. RUN THE PREDICTIONS

