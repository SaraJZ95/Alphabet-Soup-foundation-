Alphabet Soup Funding Prediction Tool
ALL OF PROJECT HAS BEEN DONE ON COLAB I GOOGLE DRIVE
Overview

This project develops a binary classifier to predict the success potential of funding applicants for the nonprofit Alphabet Soup. The dataset provided includes features such as application type, affiliation, and income amount. The goal is to create a reliable machine learning tool for funding decisions.

Project Structure

deeplearning_challenge.ipynb: Contains code for the manually configured model.
deeplearning_challenge_optimized.ipynb: Contains code for the optimized model using Keras Tuner.
AlphabetSoupCharity.h5: Saved model from the manual configuration.
AlphabetSoupCharity_optimized.h5: Saved model from the optimized configuration.
accuracy_vs_epochs.csv: Training history for plotting accuracy vs. epochs.

Results

Manual Model:
Loss: 0.5558
Accuracy: 72.65%
Optimized Model:
Loss: 0.5522
Accuracy: 73.50%

Key Findings

The optimized model slightly outperformed the manual model but still fell short of the desired accuracy threshold (75%).
Current data and preprocessing methods may not fully capture the complexity of applicant success.
