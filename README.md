# Computer-Vision
### Background

This project is part of the Tripleten data science practium. Focuses of the project is copmuter vision image processing.

## Project Description

This project is taked with development of a model for age prediction to be used by the "GoodSeed supermarket", in order to verify age in alcohol purchases.

## Data

Files and data used for this project:

Files containing 7.6k images.

Dataset matching images to **real age** of person decpicted.

**Models evaluated:** ResNet50

## Findings

Training shows a functioning model to predict age groups that can be used for age verification in store purchases. The model however requires modifications for improvment as lowest obtained MAE sits at 3 for training set and 7 for validation set. 
This task in particular is better framed around the legal age for alcohol purchase 18+/21+ instead of trying to find a global minimum. 

## Software

**Tools:** _python_, _jupyter_

**Libraries:** _pandas_, _sklearn_, _NumPy_, _PIL_, _TensorFlow_
