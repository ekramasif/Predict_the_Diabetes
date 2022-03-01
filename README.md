# Training an Artificial Neural Network with this dataset and Predicting the Diabetes. [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ekramasif/Predict_the_Diabetes/blob/main/LICENSE)

## About Dataset:
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

## Training/Validation Split:
#### I use to 'Randomly' select 80% data for Training and 20% data for Validation/Test purposes. Those 80-20% split should come uniformly from each of the TARGET types, meaning I was choosing exactly 40-10% data from TARGET = 0 and the other 40-10% from TARGET = 1 (but randomly within each target).

## Dataset: The dataset contains the following Columns (for clarity see the 'data.tsv'):

    1) Preg = Number of times pregnant.
    2) GLU = Plasma glucose concentration a 2 hours in an oral glucose tolerance test
    3) BP = Diastolic blood pressure (mm Hg)
    4) ST = Triceps skin fold thickness (mm)
    5) INS = 2-Hour serum insulin (mu U/ml)
    6) BMI = Body mass index (weight in kg/(height in m)^2)
    7) DPF = Diabetes pedigree function
    8) Age = Age in years

    9) Outcome  = 1 - YES (meaning the patient might Diabetes); 0 - NO (the patient doesn't Diabetes)
    
## parameters I use

       Activation functions: Sigmoid
       Optimizer: Adam
       No. of Layers: 6 hidden layer & 1 output layer
       Units: 800, 500, 250, 150, 75, 40, 1
       Loss: binary_crossentropy
       Metrics: accuracy


<p align="center">
  <a href="https://ekramasif.me">
    <img align="center" src="https://raw.githubusercontent.com/ekramasif/ekramasif/main/EkramAsif.gif" width="50%">
  </a>
</p>
