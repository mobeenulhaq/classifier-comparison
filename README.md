# Penguin and Abalone Species Classifier

This project involves the implementation of various machine learning classifiers to predict penguin species and the sex of abalone based on physical features.

## Overview

The project is structured as follows:
1. Loading and preprocessing datasets (`penguins.csv` and `abalone.csv`).
2. Plotting class distributions.
3. Splitting datasets into training and testing sets.
4. Training and evaluating classifiers:
   - Decision Tree with default parameters (Base-DT).
   - Decision Tree with hyperparameters tuned via Grid Search (Top-DT).
   - Multi-Layer Perceptron with default parameters (Base-MLP).
   - Multi-Layer Perceptron with hyperparameters tuned via Grid Search (Top-MLP).
5. Evaluating classifiers and storing performance metrics.
6. Repeating evaluations to calculate average performance and variance.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Scikit-learn
- Pandas
- Matplotlib
- NumPy

### Installation

Clone the repository to your local machine:
```shell
git clone https://github.com/mobeenulhaq/classifier-comparison.git
```

### Running the Notebook

1. Navigate to the cloned repository's directory.
2. Start Jupyter Notebook:
```shell
jupyter notebook
```
3. Open `classifiers.ipynb`.
4. Run the cells sequentially to execute the steps of the project.

## Data

- `penguins.csv`: Contains data about penguins. The goal is to predict the species based on physical attributes.
- `abalone.csv`: Contains data about abalone. The goal is to predict the sex based on physical attributes.

## Structure of the Notebook

- **Data Preprocessing**: The data from the CSV files is loaded and preprocessed. This includes handling categorical variables and normalizing the data.
- **Exploratory Data Analysis**: Visualization of data distributions.
- **Model Training and Evaluation**: Implementation and evaluation of the classifiers.
- **Repeated Trials**: Function to perform repeated trials for assessing model stability.
- **Performance Metrics**: Output of each model's performance is written to text files.

## Output Files

- `penguin-performance.txt`: Contains performance metrics for models trained on the penguin dataset.
- `abalone-performance.txt`: Contains performance metrics for models trained on the abalone dataset.
