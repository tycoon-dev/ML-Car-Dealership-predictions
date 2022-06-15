# ML-Car-Dealership-predictions
"cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/tycoon-dev/ML-Car-Dealership-predictions/blob/main/Projeto_IA.ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    };
A python implementation predicting car prices / age / fuel type. Data scrapped from StandVirtual and used for training the model.


A dataset was created by scrapping the website Standvirtual, a platform dedicated to sell both used and new cars in Portugal. Using HTML requests
and Regex, Important features were extracted (e.g: Car price, Car brand, Fuel Type, Engine power, etc)

Car price and Age prediction implements both Linear Regression using SKlearn and Catboost Regressor
Fuel type prediction implements Classification models like Kmeans and Catboost Classificator

