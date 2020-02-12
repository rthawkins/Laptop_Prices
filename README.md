### <a href="https://rthawkins.github.io/laptop_predictive_models/" target="_blank">Click here to play!</a>



# Project Overview

The goal of this project was to create a models to predict the price of a laptop based on product attributes.  There will be an interactive [webpage](https://nu-datacamp.github.io/Laptop_Prices/) that allows users to guess a laptop's price based on its attributes and compare their estimate to that of three machine trained models.

# Data Source

Laptop data was pulled from [Kaggle](https://www.kaggle.com/ionaskel/laptop-prices), and includes ~1,300 laptops.  Product attributes include:

- Company
- Product Name
- CPU
- Memory
- GPU
- Operating System
- RAM
- Screen Size
- Weight

# Data Models

Three data models were trained on 976 laptops attributes and their price.  When [testing the models](https://github.com/rthawkins/laptop_predictive_models/blob/master/LR_RF_testing_clean.ipynb) against 326 laptops, their difference to the actual prices is:

1. Linear Regression (25.2%)
2. Random Forest (18.7%)
3. Neural Networks (19.5%)

More detailed information on the models can be found in the model testing [PowerPoint presentation](https://github.com/rthawkins/laptop_predictive_models/blob/master/model_testing_explanation.pptx).

# Deployment

The web page was created using GitHub pages.

# Using the Webpage
The webpage is setup as a game and challenge to the user.  A laptop and its attributes are displayed on screen, and a user is asked to entered their estimated price.  After clicking on the "Run Results" button, each of the three models estimates will also be displayed.  Whichever estimate is closest to the actual laptop price is declared the winner (… not Price is Right rules... its ok to go over).

It's important to note that any of the laptops displayed have not been seen by the trained models.








