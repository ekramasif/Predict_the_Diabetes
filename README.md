# Training an Artificial Neural Network with this dataset and Predict the Diabetes.

## Training/Validation Split:
### I use to 'Randomly' select 80% data for Training and 20% data for Validation/Test purposes. Those 80-20% split should come uniformly from each of the TARGET types, meaning you have to choose exactly 40-10% data from TARGET = 0 and the other 40-10% from TARGET = 1 (but randomly within each target).

## Dataset: The dataset contains the following Columns (for clarity see the 'data.xlsx'):

    1) Preg = Number of times pregnant.
    2) GLU = Plasma glucose concentration a 2 hours in an oral glucose tolerance test
    3) BP = Diastolic blood pressure (mm Hg)
    4) ST = Triceps skin fold thickness (mm)
    5) INS = 2-Hour serum insulin (mu U/ml)
    6) BMI = Body mass index (weight in kg/(height in m)^2)
    7) DPF = Diabetes pedigree function
    8) Age = Age in years

    9) Outcome  = 1 - YES (meaning the patient might Diabetes); 0 - NO (the patient doesn't Diabetes)
    
##parameters I use

       Activation functions: Sigmoid
       Optimizer: Adam
       No. of Layers: 6 hidden layer & 1 output layer
       Units: 800, 500, 250, 150, 75, 40, 1
       Loss: binary_crossentropy
       Metrics: accuracy


