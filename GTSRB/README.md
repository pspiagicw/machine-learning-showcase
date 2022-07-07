<div align="center">

# GTSRB

</div>

## Project Structure
The current project is in the form of a simple Jupyter Notebook.
GitHub can display Jupyter Notebook as of 2022.

You can read the Jupyter Notebook directly or 
just browse through this README to get a gist of the problem statement and solutions provided.

## Problem Statement
The aim of this project is to achieve decent accuracy on the German Traffic Sign Recognition using Machine Learning techniques.

GTSRB is a dataset where multiple road signs are provided with 1000+ images on each one of them with different angles and lighting conditions.
The most useful task is to classify it using Machine Learning.

The data is clean and available for anyone to download.

## Approach

The most simple approach is to train a CNN classifier. But this only yields 70~80% accuracy before it faces overfitting.
What follows is a unique display of how to tame a overfitted model.

This includes Image augmentation , Model Regularization and others.

Finally the model achieves 95% accuracy.
It's accuracy can be taken higher , but it requires more time and computing power.

## Code

See [this](./gtsrb.ipynb) for information.
